# ***Problem Domain, Objects, and the DOM.***
## **JavaScript Object Literal :**
***A JavaScript object literal is a comma-separated list of name-value pairs wrapped in curly braces. Object literals encapsulate data, enclosing it in a tidy package. This minimizes the use of global variables which can cause problems when combining code.***

***The following demonstrates an example object literal:***

var myObject = {

    sProp: 'some string value',
    numProp: 2,
    bProp: false
};

## **Why and How We Use Object Literals :**
Several JavaScripts from dyn-web use object literals for setup purposes. Object literals enable us to write code that supports lots of features yet still provide a relatively straightforward process for implementers of our code. No need to invoke constructors directly or maintain the correct order of arguments passed to functions. Object literals are also useful for unobtrusive event handling; they can hold the data that would otherwise be passed in function calls from HTML event handler attributes.

# **Document Object Model (DOM)**
### The **Document Object Model (DOM)** connects web pages to scripts or programming languages by representing the structure of a document—such as the HTML representing a web page—in memory. Usually it refers to JavaScript.
### The DOM represents a document with a logical tree. Each branch of the tree ends in a node, and each node contains objects. DOM methods allow programmatic access to the tree. With them, you can change the document's structure, style, or content.

## THE DOM TREE IS A MODEL OF A WEB PAGE
***As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes.***

***Each node is an object with methods and properties.
Scripts access and update this DOM tree (not the source HTML file).
Any changes made to the DOM tree are reflected in the browser.***

# ![DOM](https://upload.wikimedia.org/wikipedia/commons/5/5a/DOM-model.svg)

# WORKING WITH THE DOM TREE

### Accessing and updating the DOM tree involves two steps:

1. **Locate the node that represents the element you want to work with.**
2. **Use its text content, child elements, and attributes.**

#### For Reference :
[***MDN.***](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction) 