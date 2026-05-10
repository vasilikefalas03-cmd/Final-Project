An array is an object that holds values in memory.
In order for it to work, you will the type of elements(the type of the array i.e int, string, float).
And, you will need the number of elements it can contain(how big the array is going to be).
A couple of examples of how they would look:
int[] primeNumbers; this declares the primeNumbers.
primeNumbers = new int[5]; this creates the array, filling with default values.

int[] primeNumbers={2,3,5,7,11}; this declares and initializes the array with actual values.
int[] primeNumbers = new int[5]; this declares and instantiates the array, filling it with default values.

You can trace an array by drawing an array, putt in any numbers and two algorithms in order to change the array.
An example of how this would look looks like this:
int[] id = {2, 0, 2, 5, 2, 1, 1, 1, 7};
int n = id.Length;

for (int i = 0; i < n -1; i++)
{
    int min-idx = i;
    for (int j = i + 1; j < n; j++)
    {
        if (id[j] < id[min-idx])
            min-idx = j;
    }
    swap(id[min-idx], id[i]);
}

There's one more function i want to talk about, it's called foreach.
It can be used to iterate over an array.
An example looks like this:
//foreach (var elem in arrayName)
foreach (int elem in arrayName)
{
    C.WL(elem)
}
// var while infer the type of the array
