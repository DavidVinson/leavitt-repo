| Base Learning Objectives                                                | Complete? |
| ----------------------------------------------------------------------- | :-------: |
| Source javascript files into index.html                                 |    yes    |
| Create a variable and set its value                                     |    yes    |
| Arrays: create an array and set initial values                          |    yes    |
| Arrays: add items to an array                                           |    yes    |
| Arrays: remove an item from an array                                    |    yes    |
| Functions: call the `sumTiles` function and pass an argument            |    yes    |
| Functions: function returns total tiles score                           |    yes    |
| Functions: returned value assigned to `myScore` variable                |    yes    |
| Loops: write a loop that totals properties from objects within an array |    yes    |
| Conditionals: compare numbers and determine which is higher             |    yes    |

---

### Notes:

- part4: the array method "pop()" does not take an argument: `let removedTile = myScrabbleTiles.pop(-1);`. it should be `let removedTile = myScrabbleTiles.pop();`

- part8: the parameter "checkScore" was not used in the functional scope.

```
  function checkHighScore (checkScore){
  if (myScore > highScore){

      highScore = myScore;

      console.log(`New Highscore: `, highScore);

  } else { //do nothing
  }
  } // end function checkHighScore

checkHighScore(myScore);

```

---

| General Items                                           | Complete? |
| ------------------------------------------------------- | :-------: |
| Proper variable scoping                                 |    yes    |
| More than 2 git commits descriptive of the changes made |    yes    |
| Code is consistently formatted                          |    yes    |
| Appropriate amount of code comments                     |    no     |

---

# Feedback:

Nice work Noah!

- well organized and clean code. you are getting better at putting code comments in describing what a function should do and what should be expected as a return value.

- Could use more frequent code commits.
