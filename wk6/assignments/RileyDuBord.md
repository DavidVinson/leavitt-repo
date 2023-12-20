Hey Riley. General comments about the project.

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

- carefull when using an 'id' that is the same or similar to an element tag. it all works, but just name it something more directly descriptive id="img-id":

```html
<input id="img" placeholder="Car Image URL" />
```

### CSS

- The page is fun to use! Great ui/ux. Form at the top, and list items below along with a running total of the garage. Well done!

- Really like the animation!

### JS

- Nice use of functions that do a specific job, like the totaling of the garage, and the function that puts the total on the DOM. Separation of work is a great idea!

- Nice comments that clearly state what the code is doing. Great way to troubleshoot if something is not doing what you think it's doing.

- Good control of the DOM and the garage list.

- Overall, well done! The idea of getting inputs off the DOM, DOM manipulation, and such is web app bread and butter. Soon, we will introduce external libraries that will make this process even better!
