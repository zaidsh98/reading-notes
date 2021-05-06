# Logical Operators 


## Logical AND (&&)
  **expr1 && expr2**  *Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false.*


## Logical OR (||)
	expr1 || expr2	Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, || returns true if either operand is true; if both are false, returns false.


## Logical NOT (!)

	!expr	Returns false if its single operand that can be converted to true; otherwise, returns true 

# LOOPS :


***Loops are used in JavaScript to perform repeated tasks based on a condition. Conditions typically return true or false when analysed. A loop will continue running until the defined condition returns false.***

**The three most common types of loops are :**
* for
* while
* do while

## for statement :

**A for loop repeats until a specified condition evaluates to false.**
> var arr = [ 1, 2, 3 ];

>for (var i = 0; i <= arr.length; i++)

>{ console.log(arr[i]); }

## while statement:

**A while statement executes its statements as long as a specified condition evaluates to true.**

>let n = 0;

>let x = 0;

>while (n < 3){

 > n++;
  >x += n;
>}

## Do while statement:

**The do...while statement repeats until a specified condition evaluates to false.**

>let i = 0;

>do {
  >i += 1;
  >console.log(i);
  
>} while (i < 5);
