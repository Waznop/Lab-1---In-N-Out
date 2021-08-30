# Lab 1: In-N-Out

In this lab, you will learn how to:
- modify a program's return code
- manage inputs and outputs
- use `string` and `int` variables

## Prerequisites

- Make sure you've completed [Lab 0](https://docs.google.com/document/d/1U18nZ7KjhPrxclvYvATiP4OdcwpzRe9hSNo0EBrzdzo/edit?usp=sharing) and know how to work on Replit & submit assignments on Gradescope.

## Question 1: oops.cpp

Programs can return exit codes that aren't 0. Usually this indicates an error. Write the `oops` program so that it returns an exit code of 1.

You can do this using a very similar process to how you wrote the `hello_world`
program in Lab 0. Here's a summary of the steps (if you're unsure, refer back to [Lab 0](https://docs.google.com/document/d/1U18nZ7KjhPrxclvYvATiP4OdcwpzRe9hSNo0EBrzdzo/edit?usp=sharing)):

1. Open the `question1/oops.cpp` file.
2. Follow the instructions in all TODO comments. Don't forget to remove the comments when you are done!
3. Compile your program: `$ g++ question1/oops.cpp` or `$ cd question1` then `$ g++ oops.cpp`.
4. Run your program: `$ ./a.out`.
5. Check the exit code to make sure your program returns an exit code of 1: `$ echo $?`.

## Question 2: echo.cpp

Pretend you're building a cashier bot for a burger restaurant. Right now, all it does is ask the customer how many burgers they want. We want the bot to repeat the number back to the customer so they can confirm the order.

Complete the `echo` program.

### Hint: Variables and `cin`

You can store a value into a **variable** in order to use it later.

A variable needs to be declared before you can use it. Each variable needs a type and a name. For example, you can declare a variable using `string username;` or `int num_students;`.

After a variable is declared, it needs to have a value assigned to it. One way to do this is to store the user's input inside a variable named `x` with `cin >> x;`.

You can print the value stored in a variable named `x` using `cout << x;`. Recall that you can print multiple things in a row like this: `cout << "x has a value of " << x << "!" << endl;`.

## Question 3: greet.cpp

In order to make the customer feel more welcomed, we want the bot to ask for their name and greet them to start the conversation.

Complete the `greet` program.

### Hint: Declaring variables

1. Choose the correct type for your variable. Should a name be a `string` or an `int`?
2. You can name a variable whatever you want, but it is best for variable names to be informative and explain what is stored inside that variable. For example, `asdfjkl` would be a very unhelpful name for a variable containing a person's name.
3. Once you have chosen a type and a name, declare the variable.
4. Now you can store the user's input in that variable.

## Question 4: burger_bot.cpp (bonus)

This question is for extra credits. Let's put everything together into a cashier bot for our burger restaurant.
- greet the customer
- confirm their order
- return a different exit code to signify that the program is unfinished

Complete the `burger_bot` program.

## Grading Rubric

* (60 points) Programming:
    * (20 points) for each of the `oops`, `echo` and `greet` programs:
        * (5 points) Code compiles in the autograder environment
        * (3 points) All TODO statements are removed
        * (2 points) Name is filled in
        * (10 points) Autograder test case correctness
* (40 points) Written assignment -- see Gradescope for point breakdowns
* (10 points extra credits): Autograder test case correctness for the `burger_bot` program

## Due Date

- Section A: August 31, 11:59pm
- Section B: September 2, 11:59pm

See [bit.ly/hwei-cs120-info](https://bit.ly/hwei-cs120-info) for all due dates.
