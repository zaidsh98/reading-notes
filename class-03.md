# HTML Lists , CSS Boxes and JavaScript Control Flow .
# HTML Lists :
***There are lots of occasions when we
need to use lists. HTML provides us with
three different types:***

* **Ordered lists:** are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.

* **Unordered lists:** are lists that begin with a bullet point
(rather than characters that indicate order).

* **Definition lists:** are made up of a set of terms along with the
definitions for each of those terms.

# Ordered Lists :
> ## < ol >
*The ordered list is created with
the < ol > element.*
> ## < li >
*Each item in the list is placed
between an opening < li > tag
and a closing </ li > tag. (The li
stands for list item.)*

# Unordered lists:
> ## < ul >
*The unordered list is created
with the < ul > element.*

# Definition lists:
> ## < dl >

*The definition list is created with
the < dl > element and usually
consists of a series of terms and
their definitions.
Inside the < dl > element you will
usually see pairs of < dt > and
< dd > elements.*

> ## < dt >
*This is used to contain the term
being defined (the definition
term).*

> ## < dd >
*This is used to contain the
definition.*

# CSS Boxes

## Boxes Dimention :
### *Width , Height*

By default a box is sized just big
enough to hold its contents. To
set your own dimensions for a
box you can use the height and
width properties.
The most popular ways to
specify the size of a box are
to use pixels, percentages, or
ems. Traditionally, pixels have
been the most popular method
because they allow designers to
accurately control their size.
When you use percentages,
the size of the box is relative to
the size of the browser window
or, if the box is encased within
another box, it is a percentage of
the size of the containing box.
When you use ems, the size
of the box is based on the size
of text within it. Designers
have recently started to use
percentages and ems more for
measurements as they try to
create designs that are flexible
across devices which have
different-sized screens.

## Limiting Width
### *min-width, max-width*

Some page designs expand and
shrink to fit the size of the user's
screen. In such designs, the
min-width property specifies
the smallest size a box can be
displayed at when the browser
window is narrow, and the
max-width property indicates
the maximum width a box can
stretch to when the browser
window is wide.
These are very helpful properties
to ensure that the content of
pages are legible (especially on
the smaller screens of handheld
devices). For example, you can
use the max-width property to
ensure that lines of text do not
appear too wide within a big
browser window and you can
use the min-width property
to make sure that they do not
appear too narrow.
You may find it helpful to try this
example out in your browser so
that you can see what happens
when you increase or decrease
the size of the browser window.

## Limiting Height
> ## min-height, max-height


# Borders 
## border-width
* thin
* medium
* thick

## border-style
You can control the style of a
border using the border-style
property. This property can take
the following values:

* **solid:** a single solid line
* **dotted:** a series of square dots
(if your border is 2px wide, then
the dots are 2px squared with a
2px gap between each dot)
* **dashed:** a series of short lines
* **double:** two solid lines (the
value of the border-width
property creates the sum of the
two lines)
* **groove:** appears to be carved
into the page
* **ridge:** appears to stick out from
the page
* **inset:** appears embedded into
the page
* **outset:** looks like it is coming
out of the screen
* **hidden / none:** no border is
shown

# JavaScript Control Flow :
### USING QUOTES INSIDE A STRING :
Sometimes you will want to use
a double or single quote mark
within a string.
Because strings can live in single
or double quotes, if you just
want to use double quotes in the
string, you could surround the
entire string in single quotes.
If you just want to use single
quotes in the string, you could
surround the string in double
quotes (as shown in the third line
of this code example).
You can also use a technique
called escaping the quotation
characters. This is done by
using a backwards slash (or
"backslash") before any type of
quote mark that appears within
a string (as shown on the fourth
line of this code sample).
The backwards slash tells the
interpreter that the following
character is part of the string,
rather than the end of it.

## RULES FOR NAMING VARIABLES :
### **Here are six rules you must always follow when giving a variable a name:**

>1- The name must begin with
a letter, dollar sign ($),or an
underscore (_). It must not start
with a number.

>2- The name can contain letters,
numbers, dollar sign ($), or an
underscore (_). Note that you
must not use a dash(-) or a
period (.) in a variable name.

>3- You cannot use keywords or
reserved words. Keywords
are special words that tell the
interpreter to do something. For
example, var is a keyword used
to declare a variable. Reserved
words are ones that may be used
in a future version of JavaScript.

>4- All variables are case sensitive,
so score and Score would be
different variable names, but
it is bad practice to create two
variables that have the same
name using different cases.

>5- Use a name that describes the
kind of information that the
variable stores. For example,
fi rstName might be used to
store a person's first name,
l astNarne for their last name,
and age for their age. 

>6- If your variable name is made
up of more than one word, use a
capital letter for the first letter of
every word after the first word.
For example, f i rstName rather
than fi rstnarne (this is referred
to as camel case). You can also
use an underscore between each
word (you cannot use a dash).

# Logical Operators :
## USING LOGICAL AND
***The logical AND is used to see
if the user's score is greater
than or equal to the pass mark
in both of the rounds of the test.
The result is stored in a variable
called passBoth.***

## USING LOGICAL OR & LOGICAL NOT
Here is the same test but this
time using the logical OR operator
to find out if the user has passed
at least one of the two rounds.
If they pass just one round, they
do not need to retake the test.
JAVASCRIPT
Look at the numbers stored in
the four va ri ables at the start
of the example. The user has
passed both rounds, so the
mi nPass va ri able will hold the
Boolean va lue of true.

# IF Statment :

***The if statment evaluate (or checks) a condition. If the condition evaluate to true, any statment in the subsequent code block are executed***

# IF ... ELSE STATEMENTS

if ... else statement al lows you
to provide two sets of code:
1. one set if the condition
evaluates to true
2. another set if the condition is
false