# **HTML Images, CSS Colors And Texts.**

## **Images :**
### **Adding Images :**

> ## **< img>**
To add an image into the page
you need to use an < img>
element. This is an empty
element (which means there is
no closing tag). It must carry the
following two attributes:
> **src**

This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site.
> **alt**

This provides a text description
of the image which describes the
image if you cannot see it.
>**title**

You can also use the title
attribute with the < img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.

## **Height & Width of Images :**
**You will also often see an <img>
element use two other attributes
that specify its size:**

### **height**
*This specifies the height of the
image in pixels.*

### **width**
*This specifies the width of the
image in pixels.*

# **Colors :**
## The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:

> **rgb values**

These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)

> **hex codes**

These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80
> **color names**

There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan

## **background-color :**
CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.
You can specify your choice of
background color in the same
three ways you can specify
foreground colors: RGB values,
hex codes, and color names

> ### hsl, hsla
The hsl color property has
been introduced in CSS3 as an
alternative way to specify colors.
The value of the property starts
with the letters hsl, followed
by individual values inside
parentheses for:
>### Hue

This is expressed as an angle
(between 0 and 360 degrees).
>### saturation

This is expressed as a
percentage.
>### lightness

This is expressed as a
percentage with 0% being white,
50% being normal, and 100%
being black.
The hsla color property allows
you to specify color properties
using hue, saturation, and
lightness as above, and adds a
fourth value which represents
transparency (just like the rgba
property). The a stands for:
>### alpha

This is expressed as a
number between 0 and 1.0.
For example, 0.5 represents
50% transparency, and 0.75
represents 75% transparency.

# **Texts :** 

## **Typeface Terminology :**

## **Serif :**
*Serif fonts have extra details on
the ends of the main strokes of
the letters. These details are
known as serifs.*

## **Sans-Serif :**
*Sans-serif fonts have straight
ends to letters, and therefore
have a much cleaner design.*

## **Monospace :**
*Every letter in a monospace (or
fixed-width) font is the same
width. (Non-monospace fonts
have different widths.)*

## **font-family :**
The font-family property
allows you to specify the
typeface that should be used for
any text inside the element(s) to
which a CSS rule applies.
The value of this property is the
name of the typeface you want
to use.
The people who are visiting
your site need the typeface you
have specified installed on their
computer in order for it to be
displayed.
You can specify a list of fonts
separated by commas so that,
if the user does not have your
first choice of typeface installed,
the browser can try to use an
alternative font from the list.

## **font-size :**
### **pixels**
Pixels are commonly used
because they allow web
designers very precise control
over how much space their text
takes up. The number of pixels is
followed by the letters px.

### **percentages**
The default size of text in
browsers is 16px. So a size of
75% would be the equivalent of
12px, and 200% would be 32px.

### **ems**
An em is equivalent to the width
of a letter m.
