An array is an object that holds values in memory.
In order for it to work, you will the type of elements(the type of the array i.e int, string, float).
And, you will need the number of elements it can contain(how big the array is going to be).
A couple of examples of how they would look:
int[] primeNumbers; this declares the primeNumbers.
primeNumbers = new int[5]; this creates the array, filling with default values.

int[] primeNumbers={2,3,5,7,11}; this declares and initializes the array with actual values.
int[] primeNumbers = new int[5]; this declares and instantiates the array, filling it with default values.

You can trace an array by drawing an array, put in any numbers and two algorithms in order to change the array.
An example of how this would look looks like this:
int[] grades1 = { 90, 100, 50, 75, 88, 72 }; // initializer old-school syntax
int[] grades2 = { 90, 100, 50, 75, 88, 72 }; // initializer collection syntax

grades[0] = 90;
grades[1] = 100;

for (int i = 0; i < grades.Length; i++)
{
    C.WL({i+1});
}


Another function i want to talk about is called foreach.
It can be used to iterate over an array.
An example looks like this:
//foreach (var elem in arrayName)
foreach (int elem in arrayName)
{
    C.WL(elem)
}
// var while infer the type of the array
