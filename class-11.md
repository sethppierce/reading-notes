# Audio, Video, Images

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

### Why this matters

Audio and video will always be on our pages in some capacity, so it is important for us to know how they're put onto the page and how to make them more accessible for all users.

### Video and Audio Content

Explain how the ability to use video and audio on the web has evolved since the early 2000s. We no longer use flash or silverlight and now use html elements like `<video>` and `<audio>`.

Describe the use of the src and controls attributes in the `<video>` element. source is the path to the video that plays and controls is the control interface, either the default browser or custom interface using an API.

Why is it important to have fallback content inside the `<video>` element? In case the video isn't supported as a fallback.

Write a very short story where `<audio>` and `<video>` are characters. I can't.

### A Complete Guide To Grid

How does Grid layout differ from Flex? flex is one directional, and is better for single row or column applications

Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
Grid Container is the main container that contains every other grid element.
Grid item are the direct children of the container and contain the content displayed in the grid
grid line are the dividing lines that make up the grid

### Responsive Images

Besides making a site visually appealing across different screen sizes, why should developers make images responsive? So that they remain clear on different resolution and different size devices.

Define the following `<img>` attributes srcset and sizes. Write an example of how they are used. srcset allows you to set two different sources and what size each one is, and sizes defines the screen width at which each size should be used.
If you need the size of an image to be different at a different screen size sizes would check and then the use srcset to chose which size is displayed.

How is srcset more helpful for responsive images than CSS or JavaScript? it allows you to change in one line the appropriate image to display at different resolutions.
