Hey Noah. General comments about the project.

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
| Code is consistently formatted                               |    no     |
| Input fields cleared when employee added                     |    yes    |

---

### Notes:

Nice work on the Weekend Challenge! The code commits are descriptive, but larger projects should have a few more commits.

### HTML:

- The HTML document should be formatted. Good use of targeting an element by an id.

### CSS:

- look to style the buttons as well!
- the alternate colors on the table rows is a good idea for readibility, but the table in the html does not contain a 'tbody' element, therefore, the css is not doing what it should be doing.

### JS:

- The user cannot be trusted! ha! Way to do some form and input validations. Any kind of user feedback that tells the user something did not go as exptected is a good practice.
- Nice work keeping functional scope in mind (passing the function an input argument). For example, "calculateMonthlyTotal(arraySum)" and "updatedMonthlyTotal(number)", but the parameter was not used in the functional scope. The "arraySum" was not used when doing the calculations.

```function calculateMonthlyTotal(arraySum){
       //loops through all employees
       for (let i = 0; i < allEmployees.length; i++){
            //changes string to number for addition/division
           const annualSalary = parseInt(allEmployees[i].annualSalary);
            //collecting all salaries and adding to totalMonthlyMoney
           totalMonthlyMoney += annualSalary;

        }//end for loop
```

- if time permitted, when an item is removed from the table, to adjust the total monthly amount as well.
