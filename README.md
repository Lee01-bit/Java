# Java

Variables:

Definition: A variable in JavaScript is a container that holds data values. Variables allow you to store, update, and manipulate information throughout your code.

Declaring Variables: You learned how to declare variables using the var, let, and const keywords. Each has different characteristics regarding scope and mutability.

var: Has function scope and can be redeclared.

let: Has block scope and can be reassigned but not redeclared within the same scope.
const: Also has block scope, but it cannot be reassigned or redeclared, making it ideal for values that should not change.

2. Data Types:
   
Definition: Data types in JavaScript define the type of data that a variable can hold. Understanding these types is key to performing correct operations on variables and avoiding errors.

Common Data Types:

Numbers: Used for numeric values (e.g., integers and floating-point numbers).

Strings: A sequence of characters used to represent text.

Booleans: Represents true or false, typically used in conditions and logical operations.

Arrays: A list of values, which can be of any data type, stored in a single variable.

Objects: Complex data structures that can hold multiple values and functions (methods) as properties.

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
3. 
Definition: An expression is a combination of values, variables, and operators that evaluates to a single value. Expressions can be simple (e.g., a single value or variable) or complex (involving multiple operators and operands).

Types of Expressions:

Arithmetic Expressions: Use arithmetic operators to perform calculations.

Example: let total = price * quantity;

Comparison Expressions: Use comparison operators to evaluate conditions.

Example: let isAdult = age >= 18;

Logical Expressions: Combine multiple conditions using logical operators.

Example: let canVote = (age >= 18) && (citizen === true);
