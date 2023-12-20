Hey Gus. General comments about the project.

---

| Functional Requirements                                                                              | Complete? |
| ---------------------------------------------------------------------------------------------------- | :-------: |
| jQuery sourced correctly                                                                             |     -     |
| Three inputs and button on DOM                                                                       |     y     |
| On click, the client.js file adds the car data to the array                                          |     y     |
| After a new car is added to the array, all cars in the array are re-appended on the DOM              |     y     |
| Styling in CSS file                                                                                  |     n     |
| Using `let` and `const`, no `var`                                                                    |     y     |
| Runs in browser without console errors                                                               |     y     |
| STRETCH: Inputs clear after button is clicked                                                        |     y     |
| STRETCH: Car not added to array if fields are blank (and this is communicated to the user)           |     y     |
| STRETCH: Maximum number of spaces and user is prevented from adding more                             |     y     |
| STRETCH: User is informed when garage array is at capacity                                           |     y     |
| STRETCH: Input for image url, saved with car information in object, displayed with other info on DOM |     n     |

---

### Notes:

Notes on items above.

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 4 commits                  |     y     |
| Code is correctly formatted         |     y     |
| Appropriate amount of code comments |     y     |

---

### Notes:

### HTML

- Very clean and organized.

### CSS

- It's good to focus on base functionality as the site must work first and foremost, but would like to see some css added.

### JS

- keep in mind best practice to use "===" for equality comparison in javascript. """(fieldData.length == 0 || fieldData == "" || fieldData == undefined)"""

- """render()""" function does what it needs to do...render cars! very efficient is using a loop to attach cars to the DOM. Some possible refactor to use the render function in other parts of the file, for example:

1. ```javascript
   function readyNow() {
     console.log("DOM is loaded!");
     render(); // when the document loads, render the garage
   }
   ```

2.

```javascript
function removeCar(event) {
  const deleteButton = event.target;
  const carIndex = deleteButton.closest("li");

  carIndex.remove();
  // trying to isolate the index of the car in the garage array
  console.log(carIndex.id);
  // using the ID of the cars to find out how to remove them in the array
  garage.splice(carIndex.id.substr(3, 1).value, 1);
  // trying to see what we output as a result of this
  console.log(garage);
  if (garage.length === 0) {
    render(); // when the last car is removed from the garage, render the garage
  }
}
```

3. ```javascript
   function render() {
     // update the DOM
     const carListElement = document.getElementById("carList");
     carListElement.innerHTML = "";
     if (garage.length === 0) {
       // render the garage when empty
       carListElement.innerHTML = `<li>This list is currently empty: ${garage.length} cars available.</li>`;
     } else {
       for (car of garage) {
         carListElement.innerHTML += `    <li id="car${garage.indexOf(
           car
         )}">You have a ${car.year} ${car.model}, made by ${
           car.make
         }, in the garage. <button onclick="removeCar(event)">Remove Car</button>
         </li>
      `;
       }
     }
   }
   ```

4. ```html
   <ul id="carList">
     <!-- <li>This is where the cars will go</li> -->
   </ul>
   ```

- Overall, Nice work! Very clean code and does what it needs to do. Would like to see some css added.
