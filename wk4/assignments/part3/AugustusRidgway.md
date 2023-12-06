### Part 3 `2-cart.js`

---

| Part 3 - Cart System                                                                   |   Complete?    |
| -------------------------------------------------------------------------------------- | :------------: |
| Runs in browser without console errors                                                 |      yes       |
| Created global variable for `basket` as empty array                                    |      yes       |
| `addItem` function takes in an item, adds to the array                                 |      yes       |
| `addItem` function returns true                                                        |      yes       |
| `listItems` loops over `basket` array and logs each item                               |      yes       |
| `empty` function empties the `basket` array                                            |      yes       |
| STRETCH: Added a global const named `maxItems` and set it to 5                         |      yes       |
| STRETCH: `isFull` function correctly returns boolean `false`                           |      yes       |
| STRETCH: `isFull` function correctly returns boolean `true`                            |      yes       |
| STRETCH: `addItem` function updated to use `isFull` and return `false` when full       |      yes       |
| STRETCH: `removeItem` function removes & returns the first matching item from `basket` | no, see note 1 |
| STRETCH: `removeItem` function returns null when item is not found                     |      yes       |

### Notes:

1. AssertionError: expected [ 'Kale' ] to be a string

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 3 commits                  |     n     |
| Code is correctly formatted         |     n     |
| Appropriate amount of code comments |     y     |

---

## Feedback

- """function addItem()""": note, use "===" for equality comparison.

  - first check if "isFull()", then based on the condition if isFull() === false, """basket.push(item);"""

- wwhat was expected to be logged on line 26? did the result match what you expected. troubleshoot the code if it wasn't what was expected.

- use either const/let in a for...of loop for the iterator (items in this case). """function listItems(){
  for (items of basket){
  console.log(items);
  }
  }"""

- Format the files!

- Empty an array is a tricky one and nice work coming up with a better solution than setting the array = [].

- Get into the habit of more frequent and smaller commits! This is an awesome habit to build. Aim to make these commits more task specific, so the messages better reflect the changes made. Think about this more in terms of the functionality added or changed, not how much of the assignment is done. Examples might be: `Updated HTML & added styling`, `Added basic cart functionality
