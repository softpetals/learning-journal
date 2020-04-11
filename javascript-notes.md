An EXPRESSION evaluates into (results in) a single value. Broadly speaking there are two types of expressions. 
1. Expressions that just assign a value to a variable
2. Expressions that use two or more values to return a single value.

In order for variables to be useful, it Neds to be given a value. This is done using the assignment operator (the equal sign)
   Var color = ‘beige’     —— the value color is now beige 
You can perform operation on any number of individual value to determine a single value.
   Var area = 3 * 2;
The value of area is now 6.

Expressions rely on things called OPERATORS; they allow programmers to create a single value from one or more values. 

ASSIGNMENTS OPERATORS
Assign a value to a variable 
Color = ‘beige’

ARITHMTIC OPERATORS 
Perform basic math
Area = 3 *2;
( examples:
		- addition		+ 		adds one value to another
		- subtraction 	-		Subtracts one value from another
		- division 		/		divides two values
		- multiplication 	*	multiplies two values
		- increments 	—		subtract one from the current number
		- modulus	%		divides two values and returns the remainder
Multiplication and division are performed before addition or subtraction.


STRING OPERATORS
Combine two strings
Greeting = ‘Hi’ + ‘Molly’

Programmers call the process of joining together two or more strings  to create one new string  CONCATENATION.


COMPARISON OPERATORS
Compare two values and return true or false
Buy = 3>5;

LOGICAL OPERATORS 
Combine expressions and return true or false
Buy = (5 > 3) && ( 2<4 );


PAGE 79 IS A GREAT EXAMPLE. 

	FUNCTIONS let you group a series of statements together to perform a specific task. If different parts of. Script repeat the same task, you can reuse the function. If different parts of a scrips repeat the same task, you can reuse the function (rather than repeating the same set of statements). Furthermore, the statements in a function are not always executed when a page loads, so functions also offer a way to store the steps needed to achieve a task. The script can then ask the function to perform all of those steps as and when they are required. If you are going to ask the function to perform its task later, you need to give your function a name. That name should describe the task it is performing. When you ask it to perform its task, it is known as calling the function. The steps that the function needs to perform in order to perform its task are packaged un in a code block. Code block consists of one or more statements contained within curly braces.
    Some functions need to be provided with information in order to achieve a given task. For example, a function to calculate the area of a box would need to know its width and height. Pieces of information passed to a function are known as PARAMETERS.  When you write a function and you expect it to provide you with an answer, the response is known as RETURN VALUE.	