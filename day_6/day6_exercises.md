# Chapter 3 (Functions & Scope), pages 85-99

If we have a function defined as function sayHello(){console.log("Hello!")}, what is the difference between entering sayHello and sayHello() in the console?

- sayHello is just the identifier and it will not execute the function and sayHello() is calling a function.

What is the difference between function parameters and arguments?

- Function parameters are pieces of information passed to a function. (And sometimes a function needs specific information to perform its task. When this is the case you would give the function parameters, which act like variables.) Then when you call the function (that has parameters) you will have to specify the values it should use. These are called arguments and those argument values could be passed as values or as variables.

- Another way to think about the difference between parameter and argument is that parameters do not hold any value yet. The values are held in the arguments passed. The parameters are just the variables that will hold the value.


What is the keyword return used for?

- The return keyword is used to return a value to the code that called the function.

How are local variables better than global variables? Are there instances you can think of where you might want to use a variable that is globally scoped over local?

- Global variables are stored in memory for as long as the web browser loads the webpage which means global variables take up more memory. Because of this, local variables are better in terms of memory storage. Additionally, local variables are locally scoped variables or have function-level scope so naming conflicts are not as common.

- We may want to use a global variable (like score) for a video game when we have one variable updated by multiple functions/situations and not just within the function itself.
