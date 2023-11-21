# HTML Interview Questions & Answers








### Table of Contents


| No. | Questions |
|---- | --------- 
|1  | [What is HTML?](#what-is-html)|
|2  | [What is Tag?](#what-is-tag) | 
|3  | [What is the difference between HTML elements and HTML tags?](#what-is-the-difference-between-html-elements-and-html-tags)|
|4  | [ How many types of heading does an HTML contain?](#how-many-types-of-heading-does-an-html-contain)|
|5  | [Explain the difference between div and span tags.](#Explain-the-differance-between-div-and-span-tags)|
|6  | [List on inline element & block element](#List-on-inline-element-and-block-element)|
|7  | [How to create a hyperlink in HTML?](#How-to-create-a-hyperlink-in-HTML?)|
|8  | [What is semantic Html](#What-is-semantic-Html)|
|9  | [What is the purpose of the alt attribute in an img tag?](#What-is-the-purpose-of-the-alt-attribute-in-an-img-tag?)|
|10 | [What is the difference between id and class attributes in HTML?](#What-is-the-difference-between-id-and-class-attributes-in-HTML?)|





1. ### What is HTML?
   Html is stands for Hyper Text Markup Language. it is the standard markup language used to create web pages. 

2. ### What is Tag? 
   tag is fundamental component used to define elements within a document. Tages are keywords enclosed in angle brackts (`<>`) that specify how the browser should display the content. They come in pairs: an opening tag and a closing tag.
   Opening Tag: It's the beginning of an element and contains the name of the element being defined.
       Example: <p>

   Closing Tag: It's the ending of an element and contains a forward slash before the element name to indicate the closure.
       Example: </p>

      ``` <p> This is a paragraph.</p>```


3. ### What is the difference between HTML elements and HTML tags?
   HTML elements are made up of opening and closing tages along with content. Tags mark the beginning and end of an element  and are used to define the structure of the content.
      
4. ###  How many types of heading does an HTML contain?
   The HTML contains six types of headings which are defind with the `<h1>` to `<h6>` tags. 
   `<h1>` is the largest heading tag and `<h6>` is the smallest one
    Example :- 
     <h1>Heading no. 1</h1>    
     <h2>Heading no. 2</h2>    
     <h3>Heading no. 3</h3>    
     <h4>Heading no. 4</h4>    
     <h5>Heading no. 5</h5>    
     <h6>Heading no. 6</h6> 

5. ###  Explain the difference between div and span tags.
   . `<div>`: it's a block-level element used to group HTML elements together. It typically creates a block on the webpage.
   . `<span>`: it's an inline element used for styling purpose or grouping inline elements together without changing the struture of the documents.


6. ###  List on inline element & block element 
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



7. ### How to create a hyperlink in HTML?
   The HTML provides an anchor tag to create a hyperlink that links one page to another page.
   tags can appears in any of the following ways:- 
       1. Active link - It is displayed, underlined and red.
       2. Visited link - It is displayed, underlined and purple.
       3. Unvisited link - It is displayed, underlined and blue.

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

9. ### What is the purpose of the alt attribute in an img tag?
   The `alt` attribute in the `<img>` tag provides alternative text for an image if the image cannot be displayed.It's also used by screen readers to describe the cannot to visually impaired users.

10. ### What is the difference between id and class attributes in HTML?
    `id` :- Should be unique within the documents, used to identify a spacific element for styling or scripting
    `class` :- Can be applied to multiple elements, used to categorize elements for styling or scripting.