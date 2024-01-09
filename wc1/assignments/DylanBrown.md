Hey Dylan. General comments about the project.

---

| Functional Requirements                                                            | Complete? |
| ---------------------------------------------------------------------------------- | :-------: |
| Input fields account for all of the data required                                  |    yes    |
| Submit button click appends the new employee data to the employee table on the DOM |    yes    |
| Employee entered is only added to the table once                                   |    yes    |
| Employee table has headings/th for each property                                   |    yes    |
| Monthly salary total displays the correct MONTHLY total of all employees           |    yes    |
| Monthly total is styled red if over $20,000                                        |    yes    |
| Delete button removes the selected employee data from the DOM                      |    yes    |

---

### Notes:

Notes on items above.

---

| General Items                                                | Complete? |
| ------------------------------------------------------------ | :-------: |
| More than 8 git commits                                      |    no     |
| Commits are descriptive of the changes made or feature added |    yes    |
| Correct use of id and classes                                |    yes    |
| Correct use of HTML elements                                 |    yes    |
| Appropriate amount of code comments                          |    yes    |
| Code is consistently formatted                               |    yes    |
| Input fields cleared when employee added                     |    yes    |

---

### Notes:

Nice work on the Weekend Challenge! The code commits are descriptive, but larger projects should have a few more commits.

### HTML:

- The HTML document is well formed and organized. Good use of targeting an element by an id.
- Good job on tying the input label and input field together with "for". This is good for readibility for screen readers.

### CSS:

- Incorporating flex-box is a great way to ensure the page looks good on various size screens.
- centering the form and table looks more finished, good job.
- look to style the buttons as well!
- the alternate colors on the table rows is a nice touch. Easier for the user to read.
- maybe make the Total Montly a little bigger for readability.

### JS:

- The user cannot be trusted! ha! Way to do some form and input validations. Any kind of user feedback that tells the user something did not go as exptected is a good practice.
- Nice work keeping functional scope in mind (passing the function an input argument). For example, "updateTable()" and "calculateBudget()"
- Good use of array methods on the DOM elements. Even better was converting the 'array-like' DOM object into an actual array! Now there are additional methods to help work with the data. nice work!
