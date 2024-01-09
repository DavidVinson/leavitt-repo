Hey Riley. General comments about the project.

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

- Nice use of 'required' on the form inputs. Users cannot be trusted! Letting the user know something is not right, or has not been submitted b/c of an error is what is expected in handling forms. As we get into more backend functions, the actual user validations will be handled there.

### CSS:

- css is very well organized.
- the alternate colors on the table rows is a good idea for readibility.
- nice work on conditionaly styling the buttons.
- also, the centered form and table looks more finished than if everything was justified to the left.

### JS:

- interesting way to get the form inputs!
- we could also look to do some more input validations before the the employee object is created.
- It may be better if explicitly use the event parameter versus the global window event (deprecated)`function removeRow(event) {...}`
- look to put the 'removedSalary' as a variable.
