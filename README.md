# Feynman-writing-prompts
Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old. Doing this will help you quickly discover any holes in your understanding. Ask your questions on Slack.
Variables
Variables are stored values that are given a name that can be used when running a computer program. They can be numbers, strings, boolean values, functions, null, or other values. In javascript you assign a name to a value and that becomes a variable. 
Strings
Strings are arrays that are stored in the computer which represent a string of text. The text, made up of a string of ASCII characters, is stored in a particular order, and appears as “Hello World!” or as “$2.99”. They are signified by being inside of quotes, either double or single.
Functions (arguments, return)
Functions are a piece of code that has a set of instructions for the computer to run but are not actually run unless they are called later in the program. The program recognizes the function and remembers it’s name but does not run it unless told to do so later in the code. It is written out by writing function(x). X is an argument which is something you pass into the function. There can be 0, 1, or more than one arguments passed into a function. A scale which weighs things can have an argument that is an item. If you pass the item onto the function of the scale it will weigh it and return the weight. Return is the value that the function will produce when called upon and the code is run. The first time return appears while running the code signals the computer to exit the function and produce that value in the place where the function was called.
if statements
If statements are used to create a flow of the code that the computer will run. While running your code, the program runs into an if statement which is written like this: if ( a > b ). It will evaluate the comparison it is given inside the parentheses and will run the code inside the if statement if that comparison is true. If the comparison is not true it will skip the code inside the if statement.
Boolean values (true, false)
At the heart of any code for a computer is on and off switches, represented by 1 and 0. true and false boolean values represent on and off, or 1 and 0, respectively. This is a binary value which is very useful when coding in order to give the computer a yes or no decision.
Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old. Doing this will help you quickly discover any holes in your understanding. Ask your questions on Slack.
For
The for loop is used to run a piece of code multiple times. It is done by setting a variable equal to a number, checking whether that number is less than or greater than some other number to determine the amount of times to run the code, and incrementing or decrementing the initial variable each time the loop takes place. The variable can also be multiplied or altered another way but it needs to stop at some point when it does not meet the condition set in place.
&&, ||, !
&& is a logical operator when testing conditions which means and. If && is between two boolean values both must be true, and if that is the case, the block as a whole evaluates as true. || is the or logical operator and evaluates as true if at least one of the boolean values on either side is true. ! is not, it reverses the boolean value to the right of it from true to false, and vice versa.
Arrays
Arrays are sets of values that are kept together. They store values. And array can be [ 1, 2, 3 ] or [ ‘a’ , ‘1’, ‘b’ ] or [1, ‘a’, 2] any value that can be a variable, including an array, can be stored in the array.
Git
Git is a version control software that allows the code for a program to be changed by a single person without affecting the master or production copy. The programmer who has made some possible changes can request that his changes be added to the master version and other programmers can review the changes and approve them if they are deemed to be an improvement on the old code. This creates an updated version. If the changes are not desirable they can be rejected and the master version of the code remains unchanged.
GitHub
Github is a service that creates a user friendly environment for working using Git. It allows people to make profiles and organizes the projects so that they are easier to handle for everyone.
Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old. Doing this will help you quickly discover any holes in your understanding. Ask your questions on Slack.
Objects
Objects are values that contain several values stored within a single larger value. They are each given a name or key that is followed with a colon and a value on the right of the colon. These values are known as properties. They are separated from each other by commas, and are inside of curly braces, like such:  var object1 = { key1: value1, key2: value2}
Properties
Properties are the stored values inside of objects and have a name or key, and value. They can contain any kind of value.
Methods
Methods are properties that contain values which are functions. Invoking a method of an object runs that function.
for in loop
The for in loop loops over all of the properties in an object array or other set of values and carries out a block of code for each of those values and stops when it has done so for each value. If there are 5 values in an array it will run the code 5 times even if the code simply prints out hi each time. It can also change that value or use that value.
Dot notation vs bracket notation
Dot notation is the more common way of referencing values within an object. It is written as object.property. The dot notation is used most of the time but sometimes the bracket notation is required, particularly when changing or using values or names of properties in a for each loop. In this case dot notation does not work and bracket notation is necessary. Bracket notation can also be used when names of properties start with a number. It is written as object[“nameOfProperty”] 
Feynman Writing Prompts - Write out explanations of the following concepts like you are explaining it to a 12 year old. Doing this will help you quickly discover any holes in your understanding. Ask your questions on Slack.
Callback Functions
Call back functions are functions that return another function within them and are used because you can include variables inside of a callback function, as well as counters, and loops, that allow variables to be accessed from outside of a function or count how many times a function has been called back and limit the amount of times it can be. They can also be used to store values of common callbacks and return stored values instead of running big functions many times, reducing processing time sometimes significantly, especially in databases.
Closure
Closure is the idea that functions have access to the variables within themselves, as well as variables within their parents function, and therefore any time that function is invoked it has access to the variable within the outer function even if it is being invoked somewhere else in the code.
arguments
arguments is a keyword in javascript that allows the user to work with the set of arguments sent into a function. If a function is called with 2 or 5 arguments, the arguments keyword allows the number of arguments to be accessed, and the arguments that have been sent in to be looked at individually. It does not have every property of arrays such as push() and pop() but it does have a length property. Individual arguments can be accessed by writing arguments[0] for the first one or arguments[arguments.length-1] for the last one.
Recursion
Recursion is a way code can be run by invoking a function within itself. An example is a function that finds a value on the fibonacci sequence when given its place on the sequence. If given the argument 5, it will add the value of its function with an argument equal to the given argument minus one, and since that is 4, it will re run it and get the value for 3 , which is the value for 2, which is 1, plus the value for 1 which is 1, and that 2 will be put in for 4 which will be 2 plus 1, which will be put in as 3, and the value for 3 which is 2, will be added to that, and then a value of 5 will be returned. 
prototype
prototype is a method that adds a property to each instance of something. Every object automatically given the properties under Object.prototype except in certain circumstances. If there is code that says new Cat = {}, then by writing cat.prototype one can add a property to each object that is made from that code. It is usually not advisable to modify prototypes of standard javascript objects. Your own objects’ prototypes may be modified in this way.
Constructors
Constructors are like functions, and are used to make many copies of similar code. The convention is to capitalize the first letter of the name, unlike other variables which use camelCase. They are called by writing new then the name of the constructor. a cat constructor can be made like this: function Cat () { ... } and when declaring a new cat one would say  var myCat = new Cat(); and it passes along the code in the constructor into myCat.



