# HTML Interview Questions & Answers








### Table of Contents


| No. | Questions |
|---- | --------- 
|1  | [What is HTML?](#what-is-html)|
|2  | [What is Tag?](#what-is-tag) | 
|3  | [What is the difference between HTML elements and HTML tags?](#what-is-the-difference-between-html-elements-and-html-tags)|
|4  | [How many types of heading does an HTML contain?](#how-many-types-of-heading-does-an-html-contain)|
|5  | [Explain the difference between div and span tags](#explain-the-difference-between-div-and-span-tags)|
|6  | [List on inline element and block element](#list-on-inline-element-and-block-element)|
|7  | [How to create a hyperlink in HTML?](#how-to-create-a-hyperlink-in-html)|
|8  | [What is semantic Html](#what-is-semantic-html)|
|9  | [What is the purpose of the alt attribute in an img tag?](#what-is-the-purpose-of-the-alt-attribute-in-an-img-tag)|
|10 | [What is the difference between id and class attributes in HTML?](#what-is-the-difference-between-id-and-class-attributes-in-html)|
|11 | [Explain the difference between the `<script>`, `<link>`, `<style>` tags.](#explain-the-difference-between-the-script-link-style-tags)|
|12 | [What is the purpose of the `data-` attribute in HTML?](#what-is-the-purpose-of-the-data--attribute-in-html)|
|13 | [How do you create a responsive website in HTML?](#how-do-you-create-a-responsive-website-in-html)|
|14 | [What is the purpose of the `target` attribute in `<a>` tags?](#what-is-the-purpose-of-the-target-attribute-in-a-tags)|
|15 | [Explain the difference between the `<strong>` and `<b>` tags.](#explain-the-difference-between-the-strong-and-b-tags)|
|16 | [How can you embed a video in HTML5?](#how-can-you-embed-a-video-in-html5)|
|17 | [What is purpose of the `<figure>` and `<figcaption>` tags?](#what-is-purpose-of-the-figure-and-figcaption-tags)|
|18 | [What's the purpose of the `autocomplete` attribute in HTML forms?](#whats-the-purpose-of-the-autocomplete-attribute-in-html-forms)|
|19 | [How can you embed an audio file in HTML?](#how-can-you-embed-an-audio-file-in-html)|
|20 | [Explain the difference between the `<article>` and `<section>` tags.](#explain-the-difference-between-the-article-and-section-tags)|
|21 | [How can you create a dropdown menu in HTML?](#how-can-you-create-a-dropdown-menu-in-html)|
|22 | [What is the purpose of the `iframe` tag?](#what-is-the-purpose-of-the-iframe-tag)|
|23 | [How do you add a favicon to a webpage?](#how-do-you-add-a-favicon-to-a-webpage)|
|24 | [What are empty elements in HTML? Provide examples.](#what-are-empty-elements-in-html-provide-examples)|
|25 | [Explain the purpose of the `required` attribute in HTML forms.](#explain-the-purpose-of-the-required-attribute-in-html-forms)|
|26 | [How can you embed SVG (Scalable Vector Graphics) in HTML?](#how-can-you-embed-svg-scalable-vector-graphics-in-html)|
|27 | [What is the purpose of the `defer` and `async` attributes in `<script>` tags?](#what-is-the-purpose-of-the-defer-and-async-attributes-in-script-tags)|
|28 | [Explain the difference between the `src` and `href` attributes.](#explain-the-difference-between-the-src-and-href-attributes)|
|29 | [How can you make an image a clickable link in HTML?](#how-can-you-make-an-image-a-clickable-link-in-html)|
|30 | [What is an image map?](#what-is-an-image-map)|
|31 | []()|
|32 | []()|
|33 | []()|
|34 | []()|
|35 | []()|




1. ### What is HTML?
   Html is stands for Hyper Text Markup Language. it is the standard markup language used to create web pages. 

 **[⬆ Back to Top](#table-of-contents)**

2. ### What is Tag? 
   tag is fundamental component used to define elements within a document. Tages are keywords enclosed in angle brackts (`<>`) that specify how the browser should display the content. They come in pairs: an opening tag and a closing tag.
   Opening Tag: It's the beginning of an element and contains the name of the element being defined.
       Example: <p>

   Closing Tag: It's the ending of an element and contains a forward slash before the element name to indicate the closure.
       Example: </p>

      ``` <p> This is a paragraph.</p>```

 **[⬆ Back to Top](#table-of-contents)**

3. ### What is the difference between HTML elements and HTML tags?
   HTML elements are made up of opening and closing tages along with content. Tags mark the beginning and end of an element  and are used to define the structure of the content.

 **[⬆ Back to Top](#table-of-contents)**

4. ### How many types of heading does an HTML contain?
   The HTML contains six types of headings which are defind with the `<h1>` to `<h6>` tags. 
   `<h1>` is the largest heading tag and `<h6>` is the smallest one
    Example :- 
     <h1>Heading no. 1</h1>    
     <h2>Heading no. 2</h2>    
     <h3>Heading no. 3</h3>    
     <h4>Heading no. 4</h4>    
     <h5>Heading no. 5</h5>    
     <h6>Heading no. 6</h6> 

 **[⬆ Back to Top](#table-of-contents)**

5. ### Explain the difference between div and span tags.
   `<div>`: it's a block-level element used to group HTML elements together. It typically creates a block on the webpage.
   `<span>`: it's an inline element used for styling purpose or grouping inline elements together without changing the struture of the documents.

 **[⬆ Back to Top](#table-of-contents)**


6. ###  List on inline element and block element 
   Block-level Elements:
   These elements typically start on a new line and occupy the full width available to them, pushing subsequent content ontp the next line.
   Some common block-level elements include:
   1. `<div>`: Generic container used to group elements.
   2. `<p>`: Represents a paragraph of text.
   3. `<h1>` to `<h6>`: Headings of varying sizes.
   4. `<ul>`: Unorderd list.
   5. `<ol>`: Orderd list.
   6. `<li>`: List item within a list.
   7. `<table>`: Defines a table.
   8. `<form>`: Define an HTML form.
   9. `<header>`, `<footer>`, `<nav>`, `<section>`, `<article>` :-  HTML5  semantic elements used for structural organization.

   Inline Elements:
   These elements do not start on a new line and only take up as much width as necessary.They don't force a new line to begin after them.
   Some common inline elements include: 
   1.  `<span>`:  Generic inline container.
   2.  `<a>` : Create hyperlinks.
   3.  `<strong>` and `<em>` :  Used for text formatting (bold and italic respectivly)
   4.  `<img>`: Embeds images.
   5. `<input>` : cREATES FORM INPUT FIELDS.
   6. `<br>` : Line break.
   7. `<i>`, `<u>`, `<b>` :used for italic, underline, and bold formatting 

 **[⬆ Back to Top](#table-of-contents)**


7. ###  How to create a hyperlink in HTML?
   The HTML provides an anchor tag to create a hyperlink that links one page to another page.
   tags can appears in any of the following ways:- 
   1. Active link - It is displayed, underlined and red.
   2. Visited link - It is displayed, underlined and purple.
   3. Unvisited link - It is displayed, underlined and blue.

 **[⬆ Back to Top](#table-of-contents)**

8. ### What is semantic Html
   Semantic HTML introduces elements that describe their meaning to both the browser and devlopers, improving accessibility, search engine (SEO), and the overall struture and understanding of the content.
   Example:-  insted of using a generic `<div>` to create a section on a webpage, semantic HTML encourages the use of more descriptive like `<header>`, `<footer>`, `<nav>`,
   `<article>`, `<section>`, and `<aside>`. These elements communicate the purpose and struture of their content to both machines and human developers.
     Seamantic HTML elements and their purpose:
     `<header>` :- Represents introductory content typically containing navigation, logos, or headings.
     `<footer>` :- Represents the footer of a document or section, often containing authorship information, copyright, or links.
     `<nav>` :-  Defines a section with navigation links.
     `<article>` :-  Represents a self-contained piece of content, like a blog post, article, or comment.
     `<section>` :- Defines a thematic grouping within a document.
     `<aside>` :-  Represents content tangentially related to the main content, like sidebars or callout boxes.

 **[⬆ Back to Top](#table-of-contents)**

9. ### What is the purpose of the alt attribute in an img tag?
   The `alt` attribute in the `<img>` tag provides alternative text for an image if the image cannot be displayed.It's also used by screen readers to describe the cannot to visually impaired users.

 **[⬆ Back to Top](#table-of-contents)**

10. ### What is the difference between id and class attributes in HTML?
    `id` :- Should be unique within the documents, used to identify a spacific element for styling or scripting
    `class` :- Can be applied to multiple elements, used to categorize elements for styling or scripting.

 **[⬆ Back to Top](#table-of-contents)**

11. ### Explain the difference between the `<script>`, `<link>`, `<style>` tags.
   `<script>` : Used to embed or reference Javascript code.
   `<link>` : Used to link external resources like stylesheets.
   `<style>` : Used to define internal style within the HTML documents.

 **[⬆ Back to Top](#table-of-contents)**

12. ###  What is the purpose of the `data-` attribute in HTML?
    The `data-` attributes allow you to store custom data within an HTML elements to be used by Javascript ot for other scripting purpose without affecting the rendering.

 **[⬆ Back to Top](#table-of-contents)**

13. ### How do you create a responsive website in HTML?
    Responsive design involves using CSS media queries to adjust the layout based on the device's screen size. Utilize flexible grid layouts, relative units like percentages or
    `em`/ `rem`, and media queries in CSS to create responsiveness.

 **[⬆ Back to Top](#table-of-contents)**

14. ### What is the purpose of the `target` attribute in `<a>` tags?
    The `target` attributes determines where the liked documents will open.
       `blank` opens the link in new tab/window, while `_self` opens it in the same tab/window.

 **[⬆ Back to Top](#table-of-contents)**

15. ### Explain the difference between the `<strong>` and `<b>` tags.
    `<strong>` : Indicates strong importance or emphasis, semantically conveying importance to the content.
    `<b>`: Represents bold text formatting without implying any additional importance.

 **[⬆ Back to Top](#table-of-contents)**

16. ### How can you embed a video in HTML5?
   Use the `<video>` element,spacifying the video source using the `src` attribute.
   include multiple `<source>` elements within the `<video>` tag to provide different video formats for browser compatibility.

 **[⬆ Back to Top](#table-of-contents)**

17. ### What is purpose of the `<figure>` and `<figcaption>` tags?
    `<figure>` : used to encapsulate media contet like images, videos, diagrams,etc.
    `<figcaption>`: Provides a caption or description for the content within the `<figure>` element.

 **[⬆ Back to Top](#table-of-contents)**

18. ### What's the purpose of the `autocomplete` attribute in HTML forms?
    The `autocomplete` attributes control whether a from field should have autocompplete enabled or disabled for user input.

 **[⬆ Back to Top](#table-of-contents)**

19. ###  How can you embed an audio file in HTML?
    Use the `<audio>` element, spacifying the audio source using the `src` attribute. Similar to the `<video>` tag, you can use multiple `<source>` elements within `<audio>`
    for different audio formats.

 **[⬆ Back to Top](#table-of-contents)**


20. ###  Explain the difference between the `<article>` and `<section>` tags.
    `<article>` : Represents a self-contained, independent piece of content that can stand alone.
    `<section>` : Defines a thematic grouping within a document, often used for organizing related content.

 **[⬆ Back to Top](#table-of-contents)**

21. ### How can you create a dropdown menu in HTML?
    Use the `<select>` element to create a dropdown menu and `<option>` elements to define the options within the menu.

 **[⬆ Back to Top](#table-of-contents)**

22. ### What is the purpose of the `iframe` tag?
    `<iframe>` is used to embed another HTML document within the current document, like displaying a map or including content from another website.

 **[⬆ Back to Top](#table-of-contents)**

23. ### How do you add a favicon to a webpage?
    Use the `<link>` tag in the `<head>` section with the rel="icon" attribute to specify the path to the favicon file.

 **[⬆ Back to Top](#table-of-contents)**

24. ### What are empty elements in HTML? Provide examples.
    Empty elements in HTML do not have any content between opening and closing tags. Examples include `<br>`, `<hr>`, and `<input>`. 

 **[⬆ Back to Top](#table-of-contents)**

25. ### Explain the purpose of the `required` attribute in HTML forms.
    The `required` attribute is used with form elements like `<input>` to specify that the field must be filled out before submitting the form.

 **[⬆ Back to Top](#table-of-contents)**

26. ### How can you embed SVG (Scalable Vector Graphics) in HTML?
    SVG can be embedded directly into HTML using the `<svg>` tag or linked externally using the `<img>` tag with the `src` attribute pointing to the SVG file.

 **[⬆ Back to Top](#table-of-contents)**

27. ### What is the purpose of the `defer` and `async` attributes in `<script>` tags?
    1. `defer`: Delays script execution until after the document has been parsed.
    2. `async`: Downloads the script asynchronously while continuing to parse the HTML, then executes the script when it's downloaded, potentially out of order.

 **[⬆ Back to Top](#table-of-contents)**

28. ### Explain the difference between the `src` and `href` attributes.
    1. `src`: Used in elements like` <img>`, ``<script>``, and `<iframe>` to specify the source of the external file.
    2. `href`: Used in elements like `<a>`, `<link>`, and ``<area>`` to specify the hyperlink reference or the location of the linked resource.

 **[⬆ Back to Top](#table-of-contents)**

29. ### How can you make an image a clickable link in HTML?
    Wrap the `<img>` tag within an `<a>` tag and specify the destination using the href attribute in the `<a>` tag.

**[⬆ Back to Top](#table-of-contents)**
 
30. ###  What is an image map?
    Image map facilitates you to link many different web pages using a single image.
    It is represented by `<map>` tag. 

**[⬆ Back to Top](#table-of-contents)**

