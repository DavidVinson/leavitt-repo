## Week 5:

### Part 3 - `3-music-collection.js`

---

| Part 3 - Music Collection                                                                          | Complete? |
| -------------------------------------------------------------------------------------------------- | :-------: |
| Using `let` and `const` - no `var`                                                                 |     y     |
| Functions do not create errors or exceptions in the browser console                                |     y     |
| `collection` array initialized as an empty array                                                   |     y     |
| `addToCollection` pushes record object into the array & returns the object                         |     n     |
| Tested `addToCollection` by adding 6 albums & logged results                                       |     y     |
| `showCollection` takes in an array, loops over it logging each item                                |     y     |
| Tested `showCollection` function                                                                   |     y     |
| `findByArtist` takes in an artist and returns an array of matching albums                          |     y     |
| Tested `findByArtist` function for both a match and no match                                       |     n     |
| STRETCH: `search` takes in a criteria object and returns an array of matching albums               |     -     |
| STRETCH: Added an array of `tracks` to the albums and updated functions to work with this property |     -     |
| STRETCH: All Stretch functions tested fully                                                        |     -     |
| OPTIONAL: Additional questions in HTML or comments                                                 |     -     |

---

### Notes:

- addToCollection function: There is a test error for this function. The error has to do with the parameters of the function.

"""function addToCollection(collection, title, artist, yearPublished) {
const record = {
title: title,
artist: artist,
yearPublished: yearPublished,
};
myCollection.push(record);
return record;"""

- The function takes 4 parameters: (collection, title, artist, yearPublished) - good!
- The function creates a 'record' object that uses 3 of the 4 parameters as keys - good!
- The function pushes the 'record' to array 'myCollection'.
  - use the parameter 'collection'.
- The function returns the 'record' object - good!

---

| General Items                       | Complete? |
| ----------------------------------- | :-------: |
| GitHub config correct               |     y     |
| At least 4 commits                  |     y     |
| Code is correctly formatted         |     y     |
| Appropriate amount of code comments |     -     |

---

### Notes:

Notes on items above.

## Feedback

- The function declarations are good; work on how the parameters are used in a function.

- Testing functions:
  //test for Artist found in collection
  // console.log('test for Artist found in collection: ', findByArtist(myCollection, "Nelly Furtado"));
  //
  // //test for Artist not in Collection
  // console.log('test for Artist not in Collection: ', findByArtist(myCollection, 'The Beatles'));

- You _could_ start to add more comments to your code though. A lot is said here through the console.logs and naming of functions and variables. However it is common professionally to add comments before functions to explain their inputs, output, and purpose.
