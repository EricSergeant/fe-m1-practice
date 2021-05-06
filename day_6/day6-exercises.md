# Chapter 3 (pages 85-99)

1. If we have a function defined as function sayHello(){console.log("Hello!")}, what is the difference between entering sayHello and sayHello() in the console? If we type sayHello without the parentheses we will only have it reprint the function.  If we include parentheses we will actually call the function and execute the code, causing the console to print "Hello!".

2. What is the difference between function parameters and arguments?  Pieces of information that will be passed into a function are the parameters, and they are like the aliases for values that will be passed to the function.  Arguments are when that data is passed into a function when it's called.  
  example: function fullName(firstName, lastName) // these are parameters while fullName(Ted, Lasso) // are the arguments.

3. What is the keyword return used for?  This returns the value of the code from the function being called.  

4. How are local variables better than global variables? Are there instances you can think of where you might want to use a variable that is globally scoped over local?  Local variables allow you to reuse the same variable name as occurs locally in other functions (e.g. "sum") so you don't have to complicate naming.  Global variables are useful if using the same info across multiple functions (e.g. "account name").

# Extra practice problems

### Problem one

function tellFortune(numChild, partnerName, location, jobTitle) {
  var output = `You will be a ${jobTitle} in ${location}, and married to ${partnerName} with ${numChild} kids.`;
  console.log(output);
}
tellFortune(2, 'Ryan', 'Miami', 'Ship Captain');
tellFortune(3, 'Elizabeth', 'Portugal', 'Software Engineer');
tellFortune(4, 'Stacy', 'Mexico City', 'famous fraudster');

### Problem two

function calculateAge(birthYear) {
  var currentYear =  new Date().getFullYear();
  var age  = `You are either ${currentYear - birthYear} or ${(currentYear - birthYear) - 1}.`;
console.log(age);
}

calculateAge(1981);
calculateAge(1999);
calculateAge(1979);

### Problem three

function calculateSupply(age, amtPerDay) {
  var maxAge = 99
  var totalNeeded = (Math.round(amtPerDay) * 365) * (maxAge - age);
  var message = `You will need ${totalNeeded} cups of tea to last you until the ripe old age of ${maxAge}.`;
console.log(message);
}

calculateSupply(40, 3);
calculateSupply(27, 2.75);
calculateSupply(55, 1);

### Additional practice problems
[even more JavaScript practice here] (https://www.w3resource.com/javascript-exercises/javascript-basic-exercises.php#EDITOR)
