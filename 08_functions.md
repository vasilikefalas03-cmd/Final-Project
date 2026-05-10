A function is normally used when you keep finding yourself writing the same piece of code multiple times in your program or even in different programs.
It can also be used to return whatever information you're looking for, by creating a function with a return type(normally the datatype of what you're looking for.
An example of a function looks like this:
double AddTwoNumbers(double num1, double num2) // these are the parameters(the datatype and the variables)
{
    return num1 + num2; // this returns the value directly
    double sum = num1 + num2;
    return sum; // this returns a variable
}

When creatign a function, you first have to think what you want it to do.
Once you figure out what you want it to do, then it's easier to figure out what the return type would be.
There can even be a function that doesn't return anything, however you still must put a return type, but in this case, the return type would be void.

It can be confusing when you need to make one yourself and not really know what the return type should be.
I was always getting stuck on what the return type should be.
It finally made sense when i stopped looking at the return type first and started with the function name first.
