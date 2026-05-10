Now, i'd like to talk about another type of array, a 2d array.
In a 2d array, you have two array functions in one entire function.
An example looks like this:
for (int i = 0; i < n; i++)
{
    for (int j = 0; j < n; j++)
    {
        C.WL();
        C.WL();
        nums[i, j] = Convert.ToInt32(C.RL());
    }
}

There's a function you can do with a 2d array called swaping.
Swaping is when you take an array with values and you swap each value with another value in the array into whatever order you want, depending how you form the trace.
This is an example of swaping in ascending order:
for (int i = 0; i < n - 1; i++)
{
    int min_idx = i;
    for (int j = i + 1; j < n; j++)
    {
        if (id[j] < id[min_idx])
            min_idx = j;
    }
    swap(id[min_idx], id[i]);
}

with this example, every run of it will swap one value with another until all the values are in ascending order.
If all the values or in order before the final iteration, you can stop.
