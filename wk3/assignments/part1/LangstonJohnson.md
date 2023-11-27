### Assignment:

- Base
  - Does it use let/const, and no use of var?
  - Does it use the variable types appropriately (string, boolean, number)?
  - Are all questions answered with the right syntax?
  - Are both checkpoints files completed and answered correctly?
  - Are there optional questions in HTML?
  - Does it run in the browser without errors?
- Stretch
  - Does while loop log the correct values for both _number of boxes_ and _items remaining_?
  - Does the for...of loop use the correct syntax (including let)?
  - Do array manipulations use the appropriate built-in methods (eg, `.splice()`, `.sort()`, `.join()`, `.concat()`)

### Part 1, `1-array-practice.js`

---

| Functional Requirements                                        | Complete? |
| -------------------------------------------------------------- | :-------: |
| 1. Favorite Foods Array created and logged                     |     -     |
| 2. Used `.length` property to find array length                |     -     |
| 3.a Logged second item (index 1) in animal array               |     -     |
| 3.b Logged last item (index 3) in animal array                 |     -     |
| 3.c STRETCH Logged last item (length - 1) in animal array      |     -     |
| 4.a Used `.push()` to add item to end of array                 |     -     |
| 4.b Used `.unshift()` to add item to beginning of array        |     -     |
| 4.c Used `.pop()` to remove the item from end of array         |     -     |
| 4.d Used `.shift()` to remove the item from beginning of array |     -     |
| 4.e STRETCH Replaced the second item in the gem array          |     -     |
| 4.f STRETCH Sorted and reversed the gem array                  |     -     |
| 4.g STRETCH Joined the gem array into a string                 |     -     |
| 4.h STRETCH Combined the color array with the gem array        |     -     |

---

### Notes:

Notes on items above.

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     -     |
| At least 3 commits                  |     -     |
| Code is correctly formatted         |     -     |
| Appropriate amount of code comments |     -     |

---

### Notes:

Notes on items above.

## Feedback Snippets

### Use of `let` in for...of loops

When we use a for...of loop, we need to declare the new variable that represents each thing in the array:
`for(let item of supplyChannges)` Just like when we have for loops, we write `for(let i = 0;...)`

When you write `for(item of supplyChannges)` without the `let`, you technically make a secret global `var`!
