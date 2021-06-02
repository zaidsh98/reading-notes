# JS Debugging 

## JavaScript Debuggers
***Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.
Built-in debuggers can be turned on and off, forcing errors to be reported to the user.
With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.***

## A DEBUGGING WORKFLOW

 **Debugging is about deduction: eliminating potential causes of an error.
Here is a workflow for techniques you will meet over the next 20 pages.
Try to narrow down where the problem might be, then look for clues.**

WHERE IS THE PROBLEM?
First, should try to can narrow down the area where
the problem seems to be. In a long script, this is
especially important.

1. Look at the error message, it tells you:
-  The relevant script that caused the problem.

- The line number where it became a problem for
the interpreter. (As you will see, the cause of
the error may be earlier in a script; but this is the
point at which the script could not continue.)

- The type of error (although the underlying cause
of the error may be different).

2. Check how far the script is running.
Use tools to write messages to the console to tell
how far your script has executed.

3. Use breakpoints where things are going wrong.
They let you pause execution and inspect the va lues
that are stored in variables.

### WHAT EXACTLY IS THE PROBLEM?

**Once you think that you might know the rough area
in which your problem is located, you can then try to
find the actual line of code that is causing the error.**

1. When you have set breakpoints, you can see if the
variables around them have the values you would
expect them to. If not, look earlier in the script.

2. Break down I break out parts of the code to test
smaller pieces of the functionality.
- Write values of variables into the console.

- Calrfunctions from the console to check if they
are returning what you would expect them to.

- Check if objects exist and have the methods I
properties that you think they do.

3. Check the number of parameters for a function, or
the number of items in an array.
And be prepared to repeat the whole process if the
above solved one error just to uncover another .

# The console.log() Method 

If your browser supports debugging, you can use **console.log()** to display JavaScript values in the debugger window:


< script>

a = 5;

b = 6;

c = a + b;

> console.log(c);

</ script>