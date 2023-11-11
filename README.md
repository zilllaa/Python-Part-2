# Python-part-2

in this week we've learned the following things :

## 1. Break
In Python, the `break` statement is a control statement used to exit a loop prematurely. It allows you to terminate the current loop and resume execution of the program after the loop. Here's a simple explanation of how the `break` statement works:

![image](https://github.com/pritaaa/Python-part-2/assets/96106020/2eb4412f-a88c-4a2d-b335-c1ce46af7b23)

Imagine you have a loop (e.g., for or while) that is designed to run a set of instructions repeatedly until a certain condition is met. The `break` statement is used to interrupt the loop and stop its execution when a specific condition is satisfied. Once the break statement is encountered, the loop immediately exits, and the program continues with the code outside of the loop.

## 2. Continue
In Python, the `continue` statement is a control statement used within loops (such as for or while) to skip the current iteration and proceed to the next one. Here's a simple explanation of how the `continue` statement works:

![image](https://github.com/pritaaa/Python-part-2/assets/96106020/6a6b7a0a-6f96-4252-b0eb-75d109587c40)


When a `continue` statement is encountered inside a loop, it immediately stops the current iteration of the loop and moves on to the next iteration. This means that any code following the `continue` statement within the current iteration is skipped, and the loop continues with the next iteration.

## 3. While
The `while` statement in Python is used for creating loops that continue executing a block of code as long as a specified condition is True. It repeatedly checks the condition before each iteration and stops when the condition becomes False. The `while` loop allows you to automate repetitive tasks and control the flow of your program based on changing conditions.

![image](https://github.com/pritaaa/Python-part-2/assets/96106020/87454735-4eee-4fc4-8e68-3ceb75d79ff1)


### ELse-while
In a `while` statement, the else block will always be executed when the condition in the `while` statement becomes False.

![else-while](https://github.com/pritaaa/Python-part-2/assets/96106020/f1b5e388-7342-4731-81b5-aa11bcb26e73)

## 4. List Comprehension
List comprehension offers a shorter syntax when you want to create a new list based on the values of an existing list.

-	Without list comprehension you will have to write a for statement with a conditional test inside.
  
![list-1](https://github.com/pritaaa/Python-part-2/assets/96106020/35e496b9-dced-4d95-8ae2-e9c9ac6933f8)

-	With list comprehension you can do all that with only one line of code.
  
![list-2](https://github.com/pritaaa/Python-part-2/assets/96106020/503a6726-0049-4192-b1ea-602902a4376b)

### - Condition
The condition is like a filter that only accepts the items that valuate to True.

![condition](https://github.com/pritaaa/Python-part-2/assets/96106020/cea88c7d-2687-45d3-9517-377bc9acf1d4)

### - Iterable
The iterable can be any iterable object. You can use the range() function to create an iterable.

![iterable](https://github.com/pritaaa/Python-part-2/assets/96106020/b08f19f0-1b9d-4a26-bc82-41e9c86306b5)


## 5. Functions
- A function in mathematics is a process that maps an input to an output. In Python, `functions` serve a similar purpose while also being used to organize code for reusability.
- Python `functions` should ideally have a specific purpose and be designed for reusability.
- While Python provides common built-in functions, developers can also define their own custom `functions`.
![image](https://github.com/pritaaa/Python-part-2/assets/96106020/e399a58f-9fe0-4774-9465-b66c706ff5f0)

By default in Python, when a function is declared, its parameters are positioned in the order in which they were defined. For the function to be invoked correctly, the parameters must be called in the same order.

### Return
-	The function will terminate the execution of the program and simultaneously return a specific value when the return statement is used with the assigned expression.
-	The return value of a function can be stored in a variable, which distinguishes it from a void function, which has no return value. It is this defining feature that determines whether a value is returned or not.
![image](https://github.com/pritaaa/Python-part-2/assets/96106020/d03f22bb-19f9-4fa6-82c9-92e4c7ca261f)

