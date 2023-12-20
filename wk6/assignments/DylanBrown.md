Hey Dylan. General comments about the project.

---

| Functional Requirements                                                                              | Complete? |
| ---------------------------------------------------------------------------------------------------- | :-------: |
| jQuery sourced correctly                                                                             |     -     |
| Three inputs and button on DOM                                                                       |     y     |
| On click, the client.js file adds the car data to the array                                          |     y     |
| After a new car is added to the array, all cars in the array are re-appended on the DOM              |     y     |
| Styling in CSS file                                                                                  |     y     |
| Using `let` and `const`, no `var`                                                                    |     y     |
| Runs in browser without console errors                                                               |     y     |
| STRETCH: Inputs clear after button is clicked                                                        |     y     |
| STRETCH: Car not added to array if fields are blank (and this is communicated to the user)           |     y     |
| STRETCH: Maximum number of spaces and user is prevented from adding more                             |     y     |
| STRETCH: User is informed when garage array is at capacity                                           |     y     |
| STRETCH: Input for image url, saved with car information in object, displayed with other info on DOM |     y     |

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

### HTML

- Very well constructed.
- You could comment out the '<li>' on line #21 b/c your deleteCar function replaces this element when the garage is empty. Nice job on the deleteCar function.

### CSS

- Right away, the garage image is great! Sets the stage for the page.

### JS

- Nice work on the functionality of the page. It does what is expected to do...add cars and display cars!

- the 'totalPrice' function is great! Has one job and does it well.

- the 'deleteCar' function is also very concise and clear. Nice work incorporating some additional array methods to help with simplifying functionality.

- the 'render' function also does its job efficiently by looping over and rendering cars from the garage and adding the delete button dynamically!

- the 'addNewCar' function is also very good. Some things to move around would be declaring the const variables at the top. This way as the code is read top-down, the variables are available to be accessed. Then moving the garage check below, you have access to the car variables and can 'clear' the input values if the garage is full. Another good function!!

```javascript
function addNewCar(event) {
  // dont forget to cancel the event's default behavior otherwise,
  // the page will reload as soon as the button is clicked ;)
  event.preventDefault();

  // get input values
  const carMake = document.getElementById("car-make");
  const carModel = document.getElementById("car-model");
  const carYear = document.getElementById("car-year");
  const carImage = document.getElementById("car-image");
  const carPrice = document.getElementById("car-price");

  if (garage.length === maxGarageSize) {
    alert("Garage is full!");
    // anything else?
    carMake.value = "";
    carModel.value = "";
    carYear.value = "";
    carImage.value = "";
    carPrice.value = "";
    return;
  }

  if (
    !carMake.value ||
    !carModel.value ||
    !carYear.value ||
    !carImage.value ||
    !carPrice.value
  ) {
    alert("Fill in all fields");
    return;
  }

  const newCar = {
    make: carMake.value,
    model: carModel.value,
    year: carYear.value,
    image: carImage.value,
    price: carPrice.value,
  };
  // add to array
  console.log(newCar);
  garage.push(newCar);
  // anything else?
  carMake.value = "";
  carModel.value = "";
  carYear.value = "";
  carImage.value = "";
  carPrice.value = "";

  totalPrice();

  render();
  // uncomment this if you need a quick test
  // alert('you clicked the button');
}
```
