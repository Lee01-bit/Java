# JavaScript

alert - used to display a alert box in your browser 

prompt- It shows a modal window with a text message, an input field for the visitor, and the buttons OK/Cancel.

confirm - The function confirm shows a modal window with a question and two buttons: OK and Cancel.

<b>e.g</b> result = prompt(title, [default]);

// is used for comments in javaScript if its only one line . /**/ used for multiple line comments 

Variables:

Definition: A variable in JavaScript is a container that holds data values. Variables allow you to store, update, and manipulate information throughout your code.

Declaring Variables: You learned how to declare variables using the var, let, and const keywords. Each has different characteristics regarding scope and mutability.

<b>var</b>: Has function scope and can be redeclared.

<b>let</b>: Has block scope and can be reassigned but not redeclared within the same scope.

<b>const</b>: Also has block scope, but it cannot be reassigned or redeclared, making it ideal for values that should not change.

2. <b>Data Types:</b>
   
Definition: Data types in JavaScript define the type of data that a variable can hold. Understanding these types is key to performing correct operations on variables and avoiding errors.

<b>Common Data Types:</b>

<b>Numbers</b>: Used for numeric values (e.g., integers and floating-point numbers).

<b>Strings:</b> A sequence of characters used to represent text.

<b>Booleans:</b> Represents true or false, typically used in conditions and logical operations.

<b>Arrays:</b> A list of values, which can be of any data type, stored in a single variable.

<b>objects:</b> Complex data structures that can hold multiple values and functions (methods) as properties.

Operators:

Definition: Operators are symbols or keywords used to perform operations on values (operands). They are the building blocks of expressions in JavaScript.

Types of Operators:

Arithmetic Operators: Used for mathematical calculations.

Examples: + (addition), - (subtraction), * (multiplication), / (division), % (modulus), and ** (exponentiation).

Assignment Operators: Used to assign values to variables.

Examples: = (assign), += (add and assign), -= (subtract and assign), *= (multiply and assign), /= (divide and assign).

Comparison Operators: Used to compare values and return a boolean (true or false).

Examples: == (equal), != (not equal), === (strict equal), !== (strict not equal), > (greater than), < (less than), >= (greater than or equal to), <= (less than or equal to).

Logical Operators: Used to combine multiple conditions.

Examples: && (AND), || (OR), ! (NOT).

Unary Operators: Operate on a single operand.

Examples: ++ (increment), -- (decrement), typeof (type of operand).

Ternary Operator: A shorthand for an if-else statement.

Example: condition ? expression1 : expression2.


2. Expressions:

    
Definition: An expression is a combination of values, variables, and operators that evaluates to a single value. Expressions can be simple (e.g., a single value or variable) or complex (involving multiple operators and operands).

Types of Expressions:

Arithmetic Expressions: Use arithmetic operators to perform calculations.

Example: let total = price * quantity;

Comparison Expressions: Use comparison operators to evaluate conditions.

Example: let isAdult = age >= 18;

Logical Expressions: Combine multiple conditions using logical operators.

Example: let canVote = (age >= 18) && (citizen === true);

<hr>

if-else Statements:

The if-else statement is a fundamental control structure that executes a block of code if a specified condition is true. If the condition is false, the else block (if provided) is executed instead.

structure

if Block: Executes when the condition is true.

else if Block: Optional; checks another condition if the previous one was false.

else Block: Executes when none of the previous conditions are met.

<br>Use Case: if-else</b> statements are used when there are multiple conditions to evaluate, with different outcomes depending on which conditions are true.

switch Statements:

