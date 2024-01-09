Hey Seid. General comments about the project.

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

Nice work on the Weekend Challenge! The code commits are descriptive, but larger projects should have a few more commits. Keep in mind that anytime a form is used that input validation may be required to keep the user informed of any problems.

### HTML:

- well organized. nice use of id to target specific elements in the document.

### CSS:

- css is very well organized.
- the alternate colors on the table rows is a good idea for readibility.
- nice work on styling the buttons.

### JS:

- look to put the 'emp' as a variable; 'let' or 'const' `
emp = {firstName: event.target.children[0].value,
        lastName: event.target.children[1].value,
        id: event.target.children[2].value,
        title: event.target.children[3].value,
        annualSalary: event.target.children[4].value,
    };`

- look to put in some input validations; to check the data before moving forward. Currently, the user can submit an 'empty' form and populate the table with empty data.
