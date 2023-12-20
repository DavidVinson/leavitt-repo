Hey Seid. General comments about the project.

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

- This was a nice feature to give user feedback.

```html
<p id="error-msg"></p>
```

### CSS

- Nice use of css classes to style 'required' fields.
- The user information in red font is a great alert to the user that something was not entered correctly, or not at all!

### JS

- Very effective functionality!

- The addEventListener to the form in the readyNow function is probably the best way to 'listen' for events. This way the event is ready to go!

- The const variables can also be declared with the other global variables in the readyNow function. This will reduce some redundancy.

```javascript
//clears input fields
function clearInputFields() {
  // const imgUrl = document.getElementById("imgUrl");
  // const addCarBtn = document.getElementById("add-car");
  // const errMsg = document.getElementById("error-msg");

  // console.log(addCarBtn);
  yearInputField.value = "";
  makeInputField.value = "";
  modelInputField.value = "";
  priceInputField.value = "";
  imgUrl.value = "";
  if (garage.length >= maxGarageCapacity) {
    yearInputField.disabled = true;
    makeInputField.disabled = true;
    modelInputField.disabled = true;
    priceInputField.disabled = true;
    imgUrl.disabled = true;
    addCarBtn.disabled = true;
    errMsg.innerHTML = "Garage is full";
  }
}
```
