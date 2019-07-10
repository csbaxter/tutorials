# While Loop

In this lab you will learn:

- What is a while loop
- How and when to use while loops

## What is a While Loop?

As we'll soon see, there are three types of loops we can use in C. While each type of loop can be made to do just about anything, each type of loop serves a particular purpose.

The **while loop** repeatedly executes a block of code as long as the condition we give it is true. We usually use a while loop when we don't know in advance how many times we want a block of code to repeat. An example might be to determine the number of times a number can be divided by 2. 

```c
int n = get_int("Enter a number: ");
int counter = 0;

while (n > 1)
{
    n = n / 2;
    counter++;
}
    
printf("Your number can be divided by 2 %i times\n", counter);
```

The syntax for a while loop is similar to the if statement, with the key word `while` replacing the `if`, where the condition is in parentheses and the block of code to execute is wrapped inside of curly braces `{``}`. But don't confuse the `while` loop with an `if` statement. Though the syntax is similar, the execution is different. The `while` loop **repeatedly** excutes the block of code while the condition is true. The `if` statement executes the block of code **once** if the condition is true.

## Forever Loop




