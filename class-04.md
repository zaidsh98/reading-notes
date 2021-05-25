# HTML Links , CSS Layout And JavaScript Functions .

## **HTML Links :**
**Links are the defining feature of the web
because they allow you to move from
one web page to another — enabling the
very idea of browsing or surfing.**

## **Writing Links** 
**Links are created using the < a> element. Users can click on anything
between the opening < a> tag and the closing </ a> tag. You specify
which page you want to link to using the href attribute.**

># < a >
***Links are created using the < a>
element which has an attribute
called href. The value of the
href attribute is the page that
you want people to go to when
they click on the link.
Users can click on anything that
appears between the opening
< a> tag and the closing </ a>
tag and will be taken to the page
specified in the href attribute.
When you link to a different
website, the value of the href
attribute will be the full web
address for the site, which is
known as an absolute URL.***

# **CSS Layout :**

## Key Concepts in Positioning El ements
### Building Blocks 
**CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.**

Block-level boxes start on a new line and act as the main building blocks
of any layout, while inline boxes flow between surrounding text. You can
control how much space each box takes up by setting the width of the
boxes (and sometimes the height, too). To separate boxes, you can use
borders, margins, padding, and background colors.
### Containing Elements :
**If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.**

It is common to group a number of elements together inside a < div>
(or other block-level) element. For example, you might group together
all of the elements that form the header of a site (such as the logo and
the main navigation). The < div> element that contains this group of
elements is then referred to as the containing element.

## **Controll ing the Position of El ements**
### CSS has the following **positioning schemes** that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

* **Normal flow :**
Every block-level element
appears on a new line, causing
each item to appear lower down
the page than the previous one.
Even if you specify the width
of the boxes and there is space
for two elements to sit side-byside,
they will not appear next
to each other. This is the default
behavior (unless you tell the
browser to do something else).

**Relative Positioning :**
This moves an element from the
position it would be in normal
flow, shifting it to the top, right,
bottom, or left of where it
would have been placed. This
does not affect the position of
surrounding elements; they stay
in the position they would be in
in normal flow.

**Absolute positioning :**
This positions the element
in relation to its containing
element. It is taken out of
normal flow, meaning that it
does not affect the position
of any surrounding elements
(as they simply ignore the
space it would have taken up).
Absolutely positioned elements
move as users scroll up and
down the page.

# **JavaScript Functions :**

## WHAT IS A FUNCTION ?
**Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of st atements).**

>function square(number) {

>  return number * number;

>}

## Why Functions ?
You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.

# Declaring Function :
**To creat a function, you give it a name and then write the statemens needed to achieve its task inside the curly bracets. This is known as a function declaration**

# Calling A Function :
**Having declared the function, you can then execute all of the statements between its curly bracets with just one line of code. this is known as calling the function.**

