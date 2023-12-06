### Part 3 `2-cart.js`

---

| Part 3 - Cart System                                                                   | Complete? |
| -------------------------------------------------------------------------------------- | :-------: |
| Runs in browser without console errors                                                 |    yes    |
| Created global variable for `basket` as empty array                                    |    yes    |
| `addItem` function takes in an item, adds to the array                                 |    yes    |
| `addItem` function returns true                                                        |    yes    |
| `listItems` loops over `basket` array and logs each item                               |    yes    |
| `empty` function empties the `basket` array                                            |    yes    |
| STRETCH: Added a global const named `maxItems` and set it to 5                         |    yes    |
| STRETCH: `isFull` function correctly returns boolean `false`                           |    yes    |
| STRETCH: `isFull` function correctly returns boolean `true`                            |    yes    |
| STRETCH: `addItem` function updated to use `isFull` and return `false` when full       |    no     |
| STRETCH: `removeItem` function removes & returns the first matching item from `basket` |    no     |
| STRETCH: `removeItem` function returns null when item is not found                     |    yes    |

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 3 commits                  |     y     |
| Code is correctly formatted         |     y     |
| Appropriate amount of code comments |     y     |

---

## Feedback

- Nice work! Really good commit frequency and descriptive messages.

- use either const/let in a for...of loop for the iterator (item in this case). """function listItems(){
  for (item of basket){
  console.log(item);
  }
  }"""

- Good rule is to put all global constants at the top of the file
