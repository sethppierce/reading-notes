# What is CSS?

[Return to Home](https://sethppierce.github.io/reading-notes)

## Links

- [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [CSS Tools: Reset CSS](https://meyerweb.com/eric/tools/css/reset/)

## Definition

CSS(Cascading Style Sheets)- controls the styling of the document

Can be used for document text styling, create a layout, apply different effects, and more.

## CSS Syntax

CSS is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

CSS properties have different allowable values, depending on which property is being specified.

## CSS modules

CSS is broken down into modules, such as background and borders. For example: background-color and border-color.

## How to add CSS

Three ways to insert CSS

- External CSS- Uses an external style sheet, can change the entire website in one file, must inculde `<link rel="stylesheet" href="mystyle.css">` in head section
- Internal CSS- An internal style sheet may be used if one single HTML page has a unique style.The internal style is defined inside the `<style>` element, inside the head section.
- Inline CSS- An inline style may be used to apply a unique style for a single element. To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

## Cascading Order

All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default

### CSS color Property

The color property specifies the color of text.

`color: {color|initial|inherit;}`

Set the text color with a HEX value:

`body {color: #92a8d1;}`

Set the text color with an RGB value:

`body {color: rgb(201, 76, 76);}`
