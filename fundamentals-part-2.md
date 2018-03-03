### What are the seven data types of javascript?
Boolean, Null, Number, Undefined, String, Symbol, Object  
### Which data type is NOT primitive?
Object
### What is the difference between single, double, and backtick quotes for strings?
Single and double quotes have the same meaning but can be used to make the other
type of quote into a literal. Otherwise it is up to programmer preference or
linter rules. The backtick is the string literal delimiter that allows multiple
line strings and the interpolation of variables or expressions.
### Which type of quote lets you embed variables/expressions into a string?
Backtick
### How do you embed variables/expressions into a string?
Using this syntax: ${variable_name}
### How do you escape characters in a string?
Using the backslash \ ex: console.log("It's \"game\" time.")
would display It's "game" time.
### What is the difference between slice/substring/substr?
slice(start, end) takes a string and "cuts" it, returning a string that begins
at the index specified by start and ends on the end index. The first character is
0, seond is 1 and so on. substr(start, length) is similar in that it returns a
string that begins on the start index and ends at length number of characters.
the substring(start, end) method works the same as slice() but has added functionality.
### What are methods?
Methods are actions that can be performed on objects. Methods can be functions
or variables.
### What are the three logical operators and what do they stand for?
&& (and)     
|| (or)    
! (not)
### What are the comparison operators?
Equal (==)
Not Equal (!=)
Strict Equal (===)
Strict Not Equal (!==)
Greater Than (>)
Greater Than or Equal to (>=)
Less Than (<)
Less Than or Equal to (<=)
### What is nesting?
Nesting is when something operates inside of something else, a function inside
another function is a nested function. Loops inside of a loop or a condition inside
another condition.
### What are truthy and falsy values?
Every value is truthy unless it is falsy.
### What are the falsy values in Javascript?
null, '' (empty string), NaN, false, 0, undefined
### What is the syntax for an if/else if/else conditional?
if (condition) {
  do something
} else if (condition2) {
  do something else
} else {
  do this
}
### What is the syntax for a switch statement?
switch(expression) {
    case n:
        code block
        break;
    case n:
        code block
        break;
    default:
        code block
}
### What is the syntax for a ternary operator?
return (isMember ? "$2.00" : "$10.00");
returns $2.00 if isMember == true or $10.00 if false
### What is the relationship between null and undefined?
undefined is when a variable is declared but has no value assigned to it. null is
an actual value, the value for nothing.
### What are conditionals?
Conditionals are used to check for a certain condition to execute specific code
for that case. git
