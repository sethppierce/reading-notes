# Forms and JS Events

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

### Why this matters

This matters because forms are an extremely useful way to accept user data and then use it with events to make something happen on the page.

### Your first Web Form. How To Structure A Web Form

Why are forms so important in web development? They allow for user input to be processed/stored.
When designing a form, what are some key things to keep in mind when it comes to user experience? To keep it simple to only get the information we need from the user as to not make the form more confusing.
List 5 form elements and explain their importance.
`<form>` the start of all form elements that defines the form.
`<label>` label is exactly what it says it is, a label for the input.
`<input>` input is where users add their input to the form.
`<textarea>` is for multiline text input.
`<button>` allows the user to submit the form once they have filled it out.

### Introduction To Events

How would you describe events to a non-technical friend? It's like pulling the trigger on a gun, it makes it fire, or makes something happen
When using the addEventListener() method, what 2 arguments will you need to provide? the name of the event we want it to register for and what happens in response to that event.
Describe the event object. Why is the target within the event object useful? it is for selecting where the event happens. Target is useful for selecting what exactly was clicked or some other event.
What is the difference between event bubbling and event capturing? bubbling starts from the element the event is on first and event capturing starts from the parent elements events down to the child element.
