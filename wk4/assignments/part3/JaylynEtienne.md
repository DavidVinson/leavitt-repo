### Part 3 `2-cart.js`

---

| Part 3 - Cart System                                                                   | Complete? |
| -------------------------------------------------------------------------------------- | :-------: |
| Runs in browser without console errors                                                 |     -     |
| Using `let` and `const`, no `var`                                                      |     y     |
| Created global variable for `basket` as empty array                                    |     y     |
| `addItem` function takes in an item, adds to the array & returns a boolean `true`      |     y     |
| `listItems` loops over `basket` array and logs each item                               |     y     |
| `empty` function resets `basket ` to empty array                                       |     y     |
| All functions called & tested in the JS file                                           |     n     |
| STRETCH: Created `const` for `maxItems`                                                |     -     |
| STRETCH: `isFull` function correctly returns boolean `true` or `false`                 |     -     |
| STRETCH: `addItem` function updated to use `isFull` and return `false` when full       |     -     |
| STRETCH: `removeItem` function removes & returns the first matching item from `basket` |     -     |
| STRETCH: `removeItem` function returns null when item is not found                     |     -     |

---

### Notes:

Notes on items above.

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 3 commits                  |     n     |
| Code is correctly formatted         |     y     |
| Appropriate amount of code comments |     y     |

---

### Notes:

Notes on items above.

---

## Feedback

- Make more frequent code commits! This is an awesome habit to build. Aim to make these commits more task specific, so the messages better reflect the changes made. Think about this more in terms of the functionality added or changed, not how much of the assignment is done. Examples might be: `Updated HTML & added styling`, `Added basic cart functionality`, or `Updated addItem to check if basket is full first`.

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
