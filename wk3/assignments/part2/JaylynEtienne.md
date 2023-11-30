### Part 2 `2-loops-practice.js`

---

| Functional Requirements                     | Complete? |
| ------------------------------------------- | :-------: |
| 1.a For loop logs from 0 to 5               |     y     |
| 1.b For loop logs from 3 to 5               |     y     |
| 1.c For loop logs even numbers from 2 to 10 |     y     |
| 1.d **STRETCH** For loop logs from 5 to 0   |     y     |
| 2.a For of loop logs all stars              |     y     |
| 3.a While loop logs all stars               |     y     |
| 3.b While loop from 0 to 5                  |     y     |
| 3.c While loop logs from 10 to 5            |     y     |

---

### Notes:

Notes on items above.

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 3 commits                  |     y     |
| Code is correctly formatted         |     y     |
| Appropriate amount of code comments |     y     |

## Feedback

- Q2.a: When we use a for...of loop, we need to declare the new variable that represents each thing in the array:
  `for (let i of stars)` Just like when we have for loops, we write `for (let i = 0;...)`

When you write `for (i of stars)` without the `let`, you technically make a secret global `var`!

- Q3.a. TODO: Write a while loop to console.log each star in the 'stars' array
  '''console.log("Some stars using while:");
  let t = 0;
  while (t < stars.length) {
  console.log(`stars in a loop ${stars[t]}`);
  t++;
  }
  '''
  The thing to remember about while loops is to declare a variable outside of the while loop. let t = 0 is outside of the while loop.

  Look at the other while loops and see if you can get those working as well. They are currently an endless loop because the condition never evaluates to false, thus ending the while loop.

- Try committing changes more often. Small commits more often is a better practice than waiting and committing one, or two large commits. It allows to check less when looking back at what has changed in a file.

- Nice work!

## Resubmit work completed
