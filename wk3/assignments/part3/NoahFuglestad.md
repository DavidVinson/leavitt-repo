### Part 3 `3-part-supply.js`

---

| Functional Requirements                                                        | Complete? |
| ------------------------------------------------------------------------------ | :-------: |
| OPTIONAL: Questions in HTML                                                    |     -     |
| JS: Use of let/const, no use of var                                            |     y     |
| JS: STRETCH: Correct syntax (including let) in for...of loop                   |     y     |
| 1. Variable of partsNeeded and value of 40 created                             |     y     |
| 2. Array of supplyChanges of numbers 3, 5, -6, 0, 7, 11                        |     y     |
| 3. Log of supplyChanges[1]                                                     |     y     |
| 4. .pop() correctly used and logged the removed item                           |     y     |
| 5. .push() the value 25 to supplyChanges                                       |     y     |
| 6A. For Loop over each item in supplyChanges                                   |     y     |
| 6B. Correctly Logs Positive Numbers                                            |     y     |
| 6C. Correctly Logs Negative Numbers                                            |     y     |
| 6D. Correctly Logs message for 0                                               |     y     |
| 7. STRETCH Uses For Of loop for refactor                                       |     y     |
| 8. STRETCH Correctly adds all supplyChanges together to equal 34               |     y     |
| 9. STRETCH Uses while loop to calculate 81 boxes filled, and 5 items remaining |     y     |

---

### Notes:

- 4: 'supplyChange.pop(-1);' the array method 'pop()' does not take an argument. Take another look into the 'pop()' method.

- 6: 'else {
  console.log("removed", -parts, "parts.");
  }'

  - the "-" before parts is not going to do what you might have intended. If this is to be concatenated to parts then look into how this could be done.

- 8: When we use a for...of loop, we need to declare the new variable that represents each thing in the array:
  `for (let parts of supplyChange)` Just like when we have for loops, we write `for(let i = 0;...)`

- When you write `for (parts of supplyChange)` without the `let`, you technically make a secret global `var`!

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 3 commits                  |     y     |
| Code is correctly formatted         |     y     |
| Appropriate amount of code comments |     y     |

---

## Feedback

- Nice work reading the README.md! Making the changes to the style.css is a detail that can easily be missed.

- Try committing changes more often. Small commits more often is a better practice than waiting and committing one, or two large commits. It allows to check less when looking back at what has changed in a file.

- Very good comments about how to handle problem #9, specifically how you describe the variables and their purpose. These types of notes/comments will help when you have to return to the code later and need a reminder of what the code is expected to do.

- Nice work!

## Resubmit work complete
