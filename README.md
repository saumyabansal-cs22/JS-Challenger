**HEY GUYS! 🙌😊**
Here I'll be exploring some javascript code challenges and listing all the documentation related to those challenges.

**1. console.log();**

console.log() simply displays information in your JavaScript console.

**2. Javascript variables:**

Variables are containers that store information for later use.
Variables can be declared using three methods:
let, const and var . 

**(i) let keyword** does not allow to redeclare the same variable using it, For example:

let num=9;

let num=0;

console.log(num);

Code written above will throw error because we have redeclared the variable num using let ....however we can reinitialize it as:

let b=8;
b=7;
console.log(b);

**var keyword** allows to redeclare and reninitialize the variable. For example:

var a=0;
var a=9;
console.log(a);

or it can be...

var g=7;
g=5;
console.log(g);

**const keyword** neither allows us to redeclare a variable nor it allows us to reinitialize the variable. For example:

const a=7;
console.log("value of a = "+a);

It is necessary to initialize the variable during its' declaration if you are using const keyword.

For example:

const a;
a=9;
console.log(a);

Above code will throw an error.


**3. Javascript Booleans**

Sometimes you might want to store information that cannot be represented by a number.

e.g, the product for which we already have a price could sometimes be on sale and sometimes not.

To store this kind of information we can use JavaScript Booleans, like so:

const isOnSale = true;

Javascript Booleans have two values -> True or false.

Sometimes we want to work with other data types, such as numbers, in a Boolean context.

Every single value in JavaScript can be transformed to a boolean value.

To do so, we can make use of the Boolean() function.

console.log(Boolean(2));

Above  code will return True.
**
**4. Operators****

-> Comparison operators - Equal
In the console.log() statement below we use the Equal operator to check whether numOne and numTwo have the same value.

