### Part 1 `1-function-practice.js`

---

| Part 1 - Function Practice                   | Complete? |
| -------------------------------------------- | :-------: |
| Runs in browser without console errors       |     y     |
| Using `let` and `const`, no `var`            |     y     |
| Functions 2-7 return correct values          |     n     |
| Functions use parameters correctly           |     n     |
| All functions called & tested in the JS file |     n     |
| STRETCH: Functions 8-10 completed correctly  |     -     |
| STRETCH: Edabit/Codewars challenge added     |     -     |

### Notes:

- 2: the function is not called with an agrument. Inspecting the code in the browser, you would have noticed "Hello, undefined!".

- 6: '''function getLast(array) {
  if (array.length > 0) {
  return array[array.length - 1];
  } else {
  return undefined;
  }
  }'''

  - the function is correct, but you did not "call" the function.

- 7: find() does not return anything: expected undefined to exist. This one was not attempted.

- These must be addressed before submitting the assignment.

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 3 commits                  |     n     |
| Code is correctly formatted         |     y     |
| Appropriate amount of code comments |     y     |

---

## Feedback

- Try committing your code more than two times. Get into a habit of making a change and committing this change. This is an awesome habit to build. Aim to make these commits more task specific, so the messages better reflect the changes made. Think about this more in terms of the functionality added or changed, not how much of the assignment is done. Examples might be: `Updated HTML & added styling`, `Added basic cart functionality`, or `Updated addItem to check if basket is full first`.

### Functions Not Called in

It is important to call and test _all_ of your functions in the JavaScript file as this gives us great insight into how well you are understanding the requirements, code, and order of code execution. We provided some examples, but you should be adding additional tests for each function to make sure it works correctly in a variety of situations.

Call your functions with in your JS file with a `console.log` that shows what you are testing and what you expect. Try to test all the expected cases for outcomes. Some examples might be:

```
// Testing both possible outcomes true/false
// Checking edge case of 0, should be false
console.log( 'isPositive(3) - should say true', isPositive(3) );
console.log( 'isPositive(0) - should say false', isPositive(0) );
console.log( 'isPositive(-3) - should say false', isPositive(-3) );
```

OR

```
// Testing addItem and listItems
console.log('Add 1) milk - true', addItem('Milk');
console.log('Call listItems:');
listItems(basket);

// Fill basket & test full
console.log('Add apple - true', addItem('apple');
console.log('Add orange - true', addItem('orange');
console.log('Add cheese - true', addItem('cheese');
console.log('Add bread - true', addItem('bread');
console.log('Add cookies - stretch full: false', addItem('cookies');
console.log('Call listItems:');
listItems(basket);

//testing empty, addItem and listItems
console.log('Empty basket');
empty(basket);
console.log('Call listItems:');
listItems(basket);
```

### Explaining confustion around arrays in the console

There are two ways you can use `console.log` to show an array:

1. As an object, which will show in the console as expandable, and will always reflect the current value of the object.

```
console.log('Basket is:', basket);
```

2. As a string, by using concatenation or a template literal. This will show a point in time value.

```
console.log(`Basket is ${basket}`);
```

### Functions not using input parameters correctly

It's important to understand how to use and handle function input parameters. The goal is to have your functions be reuseable with different input values. For example, with `helloName` you should be able to say hello to anyone, Casie, Mary, Kris, it should work with any name.

In order to do this, the name is provided when you call the function. It should not be set to a fixed value in the function itself.

```
function helloName(name) {
  return 'Hello, ' + name + '!';
}
console.log( helloName('Casie') );
console.log( helloName('Kris') );
console.log( helloName('Mary') );
```

### General - Commit Messages

It's great to see you doing multiple commits! This is an awesome habit to build. Aim to make these commits more task specific, so the messages better reflect the changes made. Think about this more in terms of the functionality added or changed, not how much of the assignment is done. Examples might be: `Updated HTML & added styling`, `Added basic cart functionality`, or `Updated addItem to check if basket is full first`.
