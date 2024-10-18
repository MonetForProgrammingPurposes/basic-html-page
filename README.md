Activity 18: Research HTML

Overview of HTML

HTML (HyperText Markup Language) is the foundational language used to create webpages and web applications. It is responsible for structuring content on the web, such as text, images, links, and multimedia, by using a system of tags. These tags form the building blocks of HTML documents and determine how elements are displayed in a browser.

Key Concepts of HTML

HTML Structure: An HTML document is made up of a series of elements that define the structure and layout of the webpage. The basic structure of an HTML document looks like this:

<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
  </body>
</html>


<!DOCTYPE html>: Declares the document type and version of HTML.

<html>: The root element of an HTML document.

<head>: Contains meta-information (like the title and links to stylesheets or scripts) about the document.

<title>: Sets the title of the webpage (displayed on the browser tab).

<body>: Contains the content that will be displayed in the browser.

HTML Tags and Elements: HTML uses tags to create elements. These tags are enclosed in angle brackets < > and usually come in pairs: an opening tag and a closing tag. The closing tag includes a forward slash /.

Examples:

<h1> to <h6>: Heading tags (h1 is the largest, h6 is the smallest).

<p>: Paragraph tag for text content.

<a href="url">: Anchor tag for creating hyperlinks.

<img src="image-url" alt="description">: Image tag to display images.

<ul> and <ol>: Unordered and ordered lists for displaying list items.

<div> and <span>: Block-level and inline elements used for styling and grouping content.

Attributes: HTML tags can have attributes that provide additional information about an element. Attributes are written inside the opening tag and typically come in key-value pairs, like id, class, or style.

Example:

<a href="https://example.com" target="_blank">Click Here</a>


href: Specifies the URL for the hyperlink.

target="_blank": Opens the link in a new tab or window.

Forms in HTML: HTML provides a way to collect user input via forms. Common form elements include:

<input>: Used to create various types of input fields (text, password, checkbox, radio, etc.).

<textarea>: Multi-line input field for text.

<button>: A clickable button element.

<select>: A drop-down menu.

<label>: Provides a label for form controls.

Example:

<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <input type="submit" value="Submit">
</form>


HTML Semantic Elements: HTML5 introduced semantic elements to make the code more meaningful and accessible. These elements describe the role of the content they contain.

Examples:

<header>: Represents the header section of a document.

<footer>: Represents the footer section of a document.

<article>: Represents independent content (like a blog post).

<section>: Groups related content in a webpage.

<nav>: Defines a section for navigation links.

<aside>: Defines content aside from the main content, like a sidebar.

Multimedia in HTML: HTML supports the embedding of multimedia content such as images, videos, and audio.

<img>: Used to embed images.

<video>: Used to embed video content.

<audio>: Used to embed audio content.

Example:

<video controls>
  <source src="video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


HTML Document Flow: HTML elements have two types of display behavior:

Block-level elements (e.g., <div>, <p>, <h1>): These elements start on a new line and take up the full width available.

Inline elements (e.g., <span>, <a>, <img>): These elements do not start on a new line and only take up as much space as necessary.

Responsive Web Design in HTML: HTML works in conjunction with CSS and JavaScript to create responsive web designs that adapt to different screen sizes and devices. One important HTML element for responsiveness is the <meta> viewport tag.

Example:

<meta name="viewport" content="width=device-width, initial-scale=1.0">


This ensures that the webpage scales properly on mobile devices.

Common HTML Use Cases

Creating a Simple Webpage: A basic webpage can be created using HTML to display content like text, images, and links.

<!DOCTYPE html>
<html>
  <head>
    <title>My Webpage</title>
  </head>
  <body>
    <h1>Welcome to My Webpage</h1>
    <p>This is a simple webpage created using HTML.</p>
    <img src="image.jpg" alt="Sample Image">
    <a href="https://example.com">Visit Example</a>
  </body>
</html>


Embedding Videos: Embedding a video into a webpage is simple with the <video> tag.

<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>


Building a Contact Form: HTML forms can be used to gather input from users. For example, a contact form might look like this:

<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name"><br>
  <label for="email">Email:</label>
  <input type="email" id="email" name="email"><br>
  <input type="submit" value="Submit">
</form>

Link to my GitHub Repository

https://github.com/MonetForProgrammingPurposes/basic-html-page

References

https://www.w3schools.com/html/html_intro.asp

https://www.w3schools.com/html/
