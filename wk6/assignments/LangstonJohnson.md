Hey Langston. General comments about the project.

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
| STRETCH: Car not added to array if fields are blank (and this is communicated to the user)           |     -     |
| STRETCH: Maximum number of spaces and user is prevented from adding more                             |     -     |
| STRETCH: User is informed when garage array is at capacity                                           |     -     |
| STRETCH: Input for image url, saved with car information in object, displayed with other info on DOM |     -     |

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

- Well constructed; good use of id's on input elements

### CSS

- Simple but effective style. The form is clear, font size good, button is clear to what it does. Nice work!
- The style on the list item is also, clear and effective. The Remove Car button (when applied css is used) is also, very standard remove item from a list structure.

### JS

- Even though the client.js loads, to ensure that the DOM is created before we enact javascript code, we create an event listener. Errors can occur if javascript is trying to access something that has not been created yet.

"""document.addEventListener('DOMContentLoaded', onReady);""" for example. We would have the function 'onReady' execute it's code when the DOM has been created.

Overall, the page looks great with how the form and the list items have been styled. the functions execute with expected behavior.
