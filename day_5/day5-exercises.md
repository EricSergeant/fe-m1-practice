# Chpt 2 JavaScript

1. How do you declare a variable. What does the equals sign really mean in JavaScript? What is it called in JavaScript?  You can declare a variable with "var variableName;" which can also happen you you assign a value to it, as in "var quantity = 4;".  The equal sign is an assignment operator which assigns the value to the variable.

2. There are three big data types in JavaScript: numbers, strings, and booleans. Describe what each of them are.  Numbers are numerical data types (i.e. numbers to be circular), strings are letters and other characters, and booleans are true/false values.

### code on page 65 not clear...check later.

3. What are the six rules for naming variables? What are a few JavaScript reserved words that you should avoid using for variable names?  "var" "let" "else" are examples.  You should avoid because these are words JS recognizes as meaningful words or commands and it'll cause confusion/errors.
  - Must begin with a letter, dollar sign, or underscore.
  - Can't use a dash or period, but can use letters, dollar signs, or underscore.
  - Cannot use keywords or reserved words.
  - Variables are case sensitive so don't create two variable names with same spelling and different cases.
  - Use a name that describes the kind of information stored in the variable.
  - Use camelCase for multiple words in a variable name.
4. How can an array be useful when dealing with multiple related values? How do you access/change a value in an array?  Rather than creating a long list of variables, an array is better.  Also helpful when you don't know how many items a list will ultimately contain. You can access or change an individual value in an array by using the index to locate it (remembering that index starts at zero so the second array value is index[1]).  You can reassign as with any variable, using the index number to indicate which value is changing (e.g. color[2] = 'beige' changes the third value in a color array to 'beige').

5. What is the difference between an expression and a statement?  An expression evalutates into a single value, either through assigning a value or calculating a value.  A statement is a single line of code, part of the instructions the computer can follow; each statement ends with a semicolon.  

6. What are three types of operators and how are they used?  In this chapter there are three: assignment, arithmetic, and string.  Assignment assigns a value to a variable, arithmetic performs basic math, and string combines two strings.  (Other types are comparison operators and logical operators, covered in chapter four.)

# Extra

"2" === 2 and "2" == 2 Why does one of those expressions return true and one return false?  First returns false, second returns true.  The first one does not convert the string "2" into the number two as it is looking for strict equality via ===.  The second one does convert (through coercion) the string "2" into the number two so both values are equal.

# Solutions to problems for Day 5:

###problem one

var numChild = 3, partnerName = "Debbie", location = "Texas", jobTitle = "Account Director";
var output = `You will be a ${jobTitle} in ${location}, and married to ${partnerName} with ${numChild} kids.`
console.log(output);

###problem two

var birthYear = 1980;
var currentYear  = 2021;
var age  = `You are either ${currentYear - birthYear} or ${(currentYear - birthYear) - 1}.`;
console.log(age);

###problem three

var currentAge = 40;
var maxAge = 98;
var amtPerDay = 3;
var totalNeeded = (amtPerDay * 365) * (maxAge - currentAge);
var message = `You will need ${totalNeeded} cups of tea to last you until the ripe old age of ${maxAge}.`;
console.log(message);
