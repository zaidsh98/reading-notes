# Basics of HTML , CSS and JavaScript .
## HTML

Headings :

# This is a Main Heading
## This is a Level 2 Heading
### This is a Level 3 Heading
#### This is a Level 4 Heading
##### This is a Level 5 Heading
###### This is a Level 6 Heading

## Paragraphs :

**Text is easier to understand when it is split up
 into units of text. For example, a book may have
 chapters. Chapters can have subheadings. Under
 each heading there will be one or more
 paragraphs.**

## Strong & Emphasis :

The use of the<strong>  element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis. By default, browsers will show the contents of a <strong>  element in bold.




The <em> element indicates emphasis that subtly changes the meaning of a sentence. By default browsers will show the contents of an <em>  element in italic.

# What is CSS ?

Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. This separation can improve content accessibility, provide more flexibility and control in the specification of presentation characteristics, enable multiple web pages to share formatting by specifying the relevant CSS in a separate .CSS file which reduces complexity and repetition in the structural content as well as enabling the .CSS file to be cached to improve the page load speed between the pages that share the file and its formatting.

## How to add CSS ?
**There are three ways of inserting a CSS :**
* Inline CSS .
* Internal CSS .
* External CSS .

## Inline 

An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

## Internal CSS

An internal style sheet may be used if one single HTML page has a unique style.

The internal style is defined inside the element, inside the head section.

## External CSS

With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the element, inside the head section.

## CSS color Property

The color property specifies the color of text.

***Example set the text-color for different elements***

> body {   color: red; }

> h1 {   color: #00ff00; }

> p.ex {   color: rgb(0,0,255); }

# JavaScript : 

JavaScript is written in plain text, just like HTML and CSS, so you do not
need any new tools to write a script. This example adds a greeting into an
HTML page. The greeting changes depending on the time of day.

When you want to use JavaScript with a web page, you use the HTML
 element to tell the browser it is coming across a script.
Its s re attribute tells people where the JavaScript file is stored.

A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.
Statements should end with a semicolon.

var today= new Date();

You should write comments to explain what your code does.
They help make your code easier to read and understand.
This can help you and others who read your code.

MULTI-LINE COMMENTS

 Th i s script displays a greeting to the user based upon the current time.
It is an example from JavaScript & jQuery book 

SINGLE-LINE COMMENTS

//Display the appropriate greeti ng based on the current time

WHAT IS A VARIABLE?

A script will have to temporarily
store the bits of information it
needs to do its job. It can store this
data in variables.

DATA TYPES

JavaScript distinguishes between numbers,
strings, and true or false values known as
Booleans.