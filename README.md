**HEY GUYS! 🙌😊**
Here I'll be exploring some javascript code challenges and listing all the documentation related to those challenges.

**1. console.log();**

console.log() simply displays information in your JavaScript console.

**2. Javascript variables**

Variables are containers that store information for later use.
Variables can be declared using three methods:
let, const and var . 

**let keyword** does not allow to redeclare the same variable using it, For example:

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

