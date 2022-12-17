# Readings: HTML Lists, Control Flow with JS, and the CSS Box Model

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

### Why this matters

Lists are important because almost always you will have something to list and learning how to properly assign them to a list and style them is important. Arrays and loops are very important, if used properly they can make your code more efficient and readable for everyone.

### Ordered and Unordered lists

1. When should you use an unordered list in your HTML document?- when listing a group of items that don't have numbered ordering and their order is meaningless.
2. How do you change the bullet style of unordered list items?- with the type attribute
3. When should you use an ordered list vs an unorder list in your HTML document?- You use an ordered list when the list has nummerical ordering or they have to be in that order
4. Describe two ways you can change the numbers on list items provided by an ordered list?- using the start attribute or type attribute

### The Box Model

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?- they are the antagonist, or opposing force, to other elements, which would be our protaganists.
2. List and describe the four parts of an HTML elements box as referred to by the box model. content box- where content is displayed, padding box- the area around the content but within the box, border box- the border around content and padding, margin box- the whitespace between the box and other elements.

### Arrays. Operators and Expressions. Conditionals. Loops

1. What data types can you store inside of an Array?strings, numbers, objects, and other arrays.
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why? 

yes it is, `console.log(people[0][1])`

```javascript
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```

3. List five shorthand operators for assignment in javascript and describe what they do.

assignment assigns value of variable to something else `=`

addition assignment adds variable to value or variable `+=`

subtraction assignment subtracts variable from value or variable `-=`

multiplication assignment multiplies variable by value or varible `*=`

division assignment divides variable by value or variable `/=`

4. Read the code below and evaluate the last expression and explain what the result would be and why.

the result would be 10dog, because adding a boolean does nothing and since dog is a string the 10 becomes a string and is added on to the end.

```javascript
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
```

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.

if I feel like making food or going out to eat, and depending on which I do the statement would be used to execute different things.

6. Give an example of when a Loop is useful in JavaScript.

when giving only a certain amount of tries and counting down those tries.
