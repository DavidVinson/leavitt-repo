Hey Andrew. General comments about the project.

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
| STRETCH: Maximum number of spaces and user is prevented from adding more                             |     y     |
| STRETCH: User is informed when garage array is at capacity                                           |     y     |
| STRETCH: Input for image url, saved with car information in object, displayed with other info on DOM |     y     |

---

### Notes:

- Pay attention to opening and closing tags; can be easily missed especially if wrapped in a template string literal
  - '''<span>text</span>'''

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 4 commits                  |     y     |
| Code is correctly formatted         |     y     |
| Appropriate amount of code comments |     y     |

### Notes:

- Nice work! Base functionality works as expected and all the stretch goals. This is the bread and butter functionality of a good web application. user interaction, user feedback, forms, updating the DOM, etc. The web app will be nothing unless it works, even if the ui/ux is amazing!

### HTML

- Well structured HTML to include comments for readability, and organized with classes and id attributes.
- Good use of of labels and connecting to an imput

### CSS

- css is always a work in progress! way to control the layout keeping flexibility in mind.
- The animation control on the page was just great!
- The animation of the car image going "into" the garage was a fun touch

### JS

- good use of alerts to keep the user informed

- functions are specific and execute as expected

- Take a look at possibly refactoring the """render(car)""" function.

  - a good refactor would be for the render function to just be responsible for rendering the garage.
  - could put in a for loop to handle what is in the garage. just a thought!

- The """removeCar()""" function is well structured using other helper functions

- The """findCarPrice()""" function. look into array method 'find' and arrow functions. This function works just fine, just a possible refactor opportunity to incorportate built-in array methods for finding objects.

- The """formatNumber()""" is a great example of the difficulty in validations from the DOM. nice work.

- I really like the separation of duties of the adding and subtracting functions to handle the total price

- I also really like the """capitalize()""" function. This was actually one of the first functions I wrote in javascript b/c I was expected javascript to have a built-in string method to do just this.

- Overall, Very nice work and the effort put into the concepts of getting information from the DOM, manipulating the information, and providing the user with the upated information. Look to refactor if time allows.
