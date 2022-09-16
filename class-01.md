# Class 1 Reading Notes

[Return to Home](https://sethppierce.github.io/reading-notes)

This section is very important because it describes the process of how a website works and how one is made.

## Questions

### Getting Started

1. Compose a short poem describing how HTTP sends data between computers.
2. Describe how HTML, CSS, and JS files are “parsed” in the browser. It is basically the order of which the files are loaded, first the HTML and while its parsing the HTML from top to bottom the `<link>` and `<script>` elements are parsed.  It compiles the parsed CSS and  JavaScript and then executes it.
3. How can you find images to add to a Website? - Using Google's License filter set to creative commons licenses.
4. How do you create a String vs a Number in JavaScript? - A number is declared without '' and a string is.
5. What is a Variable and why are they important in JavaScript? - Variables store values and those values are used to make functions work and more.

### Introduction to HTML

1. What is an HTML attribute? contain extra info not in content.
2. Describe the Anatomy of an HTMl element. opening tag content and then closing tag
3. What is the Difference between `<article>` and `<section>` element tags? section groups together a part of a page, but article makes sense on its own without the rest of the page.
4. What Elements does a “typical” website include?- `<main><body><section><p><header><nav><footer><h1,2,3,etc>`
5. How does metadata influence Search Engine Optimization? it lets search engines use the keywords to appear in searches.
6. How is the `<meta>` HTML tag used when specifying metadata? you can specify yourself as the author and other descriptions to appear in searches

### Miscellaneous

How to start to design a Website.

1. What is the first step to designing a Website?
2. What is the most important question to answer when designing a Website?

Semantics.

1. Why should you use an `<h1>` element over a `<span>` element to display a top level heading?
2. What are the benefits of using semantic tags in our HTML?

What is JavaScript?

1. Describe 2 things that require JavaScript in the Browser?
2. How can you add JavaScript to an HTML document?

## How the web works

### Clients and servers

- Clients are the typical web user's internet-connected devices (for example, your computer connected to your Wi-Fi, or your phone connected to your mobile network) and web-accessing software available on those devices (usually a web browser like Firefox or Chrome).
- Servers are computers that store webpages, sites, or apps. When a client device wants to access a webpage, a copy of the webpage is downloaded from the server onto the client machine to be displayed in the user's web browser.

### The other parts of the toolbox

- Your internet connection: Allows you to send and receive data on the web. It's basically like the street between your house and the shop.
- TCP/IP: Transmission Control Protocol and Internet Protocol are communication protocols that define how data should travel across the internet. This is like the transport mechanisms that let you place an order, go to the shop, and buy your goods. In our example, this is like a car or a bike (or however else you might get around).
- DNS: Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address before it can retrieve the website. The browser needs to find out which server the website lives on, so it can send HTTP messages to the right place (see below). This is like looking up the address of the shop so you can access it.
- HTTP: Hypertext Transfer Protocol is an application protocol that defines a language for clients and servers to speak to each other. This is like the language you use to order your goods.
- Component files: A website is made up of many different files, which are like the different parts of the goods you buy from the shop. These files come in two main types:
- Code files: Websites are built primarily from HTML, CSS, and JavaScript, though you'll meet other technologies a bit later.
- Assets: This is a collective name for all the other stuff that makes up a website, such as images, music, video, Word documents, and PDFs.

### What is JavaScript?

JavaScript is a powerful programming language that can add interactivity to a website. It was invented by Brendan Eich.

## Getting Started with HTML

### What is HTML?

HTML (HyperText Markup Language) is a markup language that tells web browsers how to structure the web pages you visit. It can be as complicated or as simple as the web developer wants it to be. HTML consists of a series of elements, which you use to enclose, wrap, or mark up different parts of content to make it appear or act in a certain way. The enclosing tags can make content into a hyperlink to connect to another page, italicize words, and so on.

### Anatomy of an HTML element

- The opening tag: This consists of the name of the element (in this example, p for paragraph), wrapped in opening and closing angle brackets. This opening tag marks where the element begins or starts to take effect. In this example, it precedes the start of the paragraph text.
- The content: This is the content of the element. In this example, it is the paragraph text.
- The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This marks where the element ends. Failing to include a closing tag is a common beginner error that can produce peculiar results.

### Attributes

Attributes contain extra information about the element that won't appear in the content. In this example, the class attribute is an identifying name used to target the element with style information.

An attribute should have:

- A space between it and the element name. (For an element with more than one attribute, the attributes should be separated by spaces too.)
- The attribute name, followed by an equal sign.
- An attribute value, wrapped with opening and closing quote marks.

### Anatomy of an HTML document

1. the doctype is a historical artifact that needs to be included for everything else to work right. `<!DOCTYPE html>` is the shortest string of characters that counts as a valid doctype. That is all you need to know!
2. `<html></html>`: The `<html>` element. This element wraps all the content on the page. It is sometimes known as the root element.
3. `<head></head>`: The `<head>` element. This element acts as a container for everything you want to include on the HTML page, that isn't the content the page will show to viewers. This includes keywords and a page description that would appear in search results, CSS to style content, character set declarations, and more. You will learn more about this in the next article of the series.
4. `<meta charset="utf-8">`: The `<meta>` element. This element represents metadata that cannot be represented by other HTML meta-related elements, like `<base>, <link>, <script>, <style> or <title>`. The charset attributes sets the character set for your document to UTF-8, which includes most characters from the vast majority of human written languages. With this setting, the page can now handle any textual content it might contain. There is no reason not to set this, and it can help avoid some problems later.
5. `<title></title>`: The `<title>` element. This sets the title of the page, which is the title that appears in the browser tab the page is loaded in. The page title is also used to describe the page when it is bookmarked.
6. `<body></body>`: The `<body>` element. This contains all the content that displays on the page, including text, images, videos, games, playable audio tracks, or whatever else.
