# Problem Domain, Objects, and the DOM

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

### Why this matters

This matters because taking time to do Domain modeling can help us visualize what code we need before we actually start doing it.
Tables are important elements for displaying information on a webpage in an organized manner.
Constructors are important because we can create multiple objects through one common function and keep our code DRY and the information more readily available.

### Domain Modeling

Explain why we need domain modeling. Domain modeling allows us to conceptualize the code we need before we actually begin coding.

### HTML Table Basics

Why should tables not be used for page layouts? They aren't automatically responsive, they reduce accessibility, and they produce tag soup.
List and describe 3 different semantic HTML elements used in an HTML `<table>`.
`<tr>` a row in the table
`<td>` a cell in the table
`<th>` the header row for a table

### Introducing Constructors

What is a constructor and what are some advantages to using it? A constructor is a function used to create objects. you can use common variables that will be in the objects and input the other variables that might change from object to object as an argument.
How does the term this differ when used in an object literal versus when used in a constructor? using .this in the constructor refers to whatever object is being created, but when used in the object it refers to that object itself.

### Object Prototypes Using A Constructor

Explain prototypes and inheritance via an analogy from your previous work experience. Performing maintainence on vehicles for common issues was like using a prototype depending on the issues, but sometimes some trucks would need more attention, or were missing something, so we could add on to that like using inheritance.
