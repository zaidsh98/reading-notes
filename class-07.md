# **HTML Tables; JS Constructor Functions**

## **HTML Tables :**
### **What's a Table?**
**A table represents information in a grid format.
Examples of tables include financial reports, TV
schedules, and sports results.**

### Basic Table St ructure :
>## < table>

The < table> element is used
to create a table. The contents
of the table are written out row
by row.
>## < tr>
You indicate the start of each
row using the opening < tr> tag.
(The tr stands for table row.)
It is followed by one or more
< td> elements (one for each cell
in that row).
> ## < td>
Each cell of a table is
represented using a < td>
element. (The td stands for
table data.)

### Table Headings:
> ### < th>
The < th> element is used just
like the < td> element but its
purpose is to represent the
heading for either a column or
a row. (The th stands for table
heading.)
Even if a cell has no content,
you should still use a < td> or
< th> element to represent
the presence of an empty cell
otherwise the table will not
render correctly. (The first cell
in the first row of this example
shows an empty cell.)
## Long Tables:

There are three elements that
help distinguish between the
main content of the table and
the first and last rows (which can
contain different content).
These elements help people
who use screen readers and also
allow you to style these sections
in a different manner than the
rest of the table (as you will see
when you learn about CSS).
> ## < thead>
*The headings of the table should
sit inside the < thead> element.*
> ## < tbody>
*The body should sit inside the
< tbody> element.*
> ## < tfoot>
*The footer belongs inside the
< tfoot> element.*

# **Functions**
**Self-contained bits of JS code that allow us to**
- ***Organize code***
- ***Reuse the same code any number of times, from different
parts of the script***

**JS supports several types of function. Commonly used types are:**
- ***Named function declaration.***
- ***Anonymous functions.***

## **A METHOD OF AN OBJECT**
***When a function is defined inside an object, it
becomes a method. In a method, this refers to the
containing object.
In the example below, the getArea () method
appears inside the shape object, so t his refers to
the shape object it is contained in:***

const shape = {

width : 500

hieght : 400

getArea : function() {

    return this.width * this.hieght;
}

};

## **FUNCTION EXPRESSION AS METHOD**

*If a named function has been defined in global
scope, and it is then used as a method of an object,
this refers to the object it is contained within.
The next example uses the same showWi dth ()
function expression as the one on the left-hand
page, but it is assigned as a method of an object.*

var width = 600;

var shape= {width : 300};

var showWidth = function(){

     document.write(this.width)

};

shape.getWidth = showWidth;
shape.getWidth();

