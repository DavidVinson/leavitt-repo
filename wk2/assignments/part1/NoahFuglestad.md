Hey Noah. General comments about the project.

---

| Part 1 -- aboutMe.js                                                     | Complete? |
| ------------------------------------------------------------------------ | :-------: |
| Use of let/const, no use of var                                          |     y     |
| Appropriate use of variable types: string, boolean, number               |     y     |
| First Name assigned to String                                            |     y     |
| Last Name assigned to String                                             |     y     |
| Full Name assigned to string concatenation                               |     y     |
| Full Name logged                                                         |     y     |
| Lucky Number assigned to Number                                          |     y     |
| Name and Lucky Number sentence logged                                    |     y     |
| Adventurous assigned to Boolean                                          |     y     |
| Food assigned to String                                                  |     y     |
| Pets assigned to Number                                                  |     y     |
| Friends Pets assigned to Number                                          |     y     |
| Add two to Pets                                                          |     y     |
| Allowed Pets assigned to a constant                                      |     y     |
| Correctly log based on adventurous boolean                               |     n     |
| Runs in browser without console errors                                   |     y     |
| "Roll the dice" conditional includes lucky number and adventurous checks |     y     |
| Pets conditional checks less than, equal and greater than                |     n     |
| OPTIONAL: Questions in HTML                                              |     -     |
| STRETCH: Correctly log the greater value (pets or friends pets)          |     y     |
| STRETCH: Correctly log pets or friends pets if they are equal            |     y     |
| STRETCH: Conditionals written with correct syntax                        |     y     |
| STRETCH: Switch statement logs the correct value                         |     y     |
| STRETCH: Ternary written with correct syntax and logic                   |     y     |

---

### Notes:

- All though this works--b/c it's JavaScript--`console.log( 'My full name is: ' + fullName );` keep in mind that another way to console log a statement plus a variable is: `console.log("My FullName", fullName);` Just in case you do NOT need your variable concatenated in a string.

- #12: When creating just a variable with nothing assigned: `let result`.

  - the Boolean variable "adventurous" was assigned earlier in the file.
  - the below snippet shows the result being assigned as a boolean (let adventurous = true)
    before the conditional, which reassigns the result to a string. Javascript will let you do this, but this is not a good idea.

  ```
  let result = adventurous;

  if(adventurous === true) {
  result = 'Adventures are great!';
  }
  else{
  result = 'How about we stay home?';
  }
  console.log( result );

  ```

  - #14 STRETCH GOAL: same problem as #12.

  - #15 STRETCH GOAL: This is done correctly! Look at this and apply to #12 and #14

---

| General Items                  | Complete? |
| ------------------------------ | :-------: |
| The assignment repo was forked |     y     |
| The correct repo was turned in |     y     |
| GitHub config correct          |     y     |
| At least 2 commits             |     y     |
| Code is correctly formatted    |     n     |

---

### Notes:

Notes on items above.

### Feedback:

- Good Work! Way to expand on creating variables and logging them. This will habit will pay off when the code gets more complex. I feel as though it was becoming clearer as you worked through the material.

- Get into a habit of formatting your files. html, css, and now .js files. If you format the aboutMe.js file, you will notice ";" semi-colons added to end of statements, and also some spacing around if/else statements. This may seem nitpicky, but want you to develop good habits. Overall, the readability of code matters and the code was pretty good, but formatting a file should be as common as saving a file. VS Code built in formatter: `Shift+Option+F`
