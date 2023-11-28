### Part 3 `3-part-supply.js`

---

| Functional Requirements                                                        | Complete? |
| ------------------------------------------------------------------------------ | :-------: |
| OPTIONAL: Questions in HTML                                                    |     -     |
| JS: Use of let/const, no use of var                                            |     y     |
| JS: STRETCH: Correct syntax (including let) in for...of loop                   |     -     |
| 1. Variable of partsNeeded and value of 40 created                             |     y     |
| 2. Array of supplyChanges of numbers 3, 5, -6, 0, 7, 11                        |     y     |
| 3. Log of supplyChanges[1]                                                     |     y     |
| 4. .pop() correctly used and logged the removed item                           |     y     |
| 5. .push() the value 25 to supplyChanges                                       |     y     |
| 6A. For Loop over each item in supplyChanges                                   |     n     |
| 6B. Correctly Logs Positive Numbers                                            |     -     |
| 6C. Correctly Logs Negative Numbers                                            |     -     |
| 6D. Correctly Logs message for 0                                               |     -     |
| 7. STRETCH Uses For Of loop for refactor                                       |     -     |
| 8. STRETCH Correctly adds all supplyChanges together to equal 34               |     -     |
| 9. STRETCH Uses while loop to calculate 81 boxes filled, and 5 items remaining |     -     |

---

### Notes:

Notes on items above.

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 3 commits                  |     n     |
| Code is correctly formatted         |     y     |
| Appropriate amount of code comments |     y     |

---

## Feedback

- Read the "README.md" file carefully. Refer to `Files Provided` Section, and update the style.css file.

- When we use a for...of loop, we need to declare the new variable that represents each thing in the array:
  `for (let item of supplyChannges)` Just like when we have for loops, we write `for (let i = 0;...)`

When you write `for (item of supplyChannges)` without the `let`, you technically make a secret global `var`!

- Q6: the loop is structured correctly, but the conditions were not.

- Try committing changes more often. Small commits more often is a better practice than waiting and committing one, or two large commits. It allows to check less when looking back at what has changed in a file.

- Nice work!
