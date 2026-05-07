A for loop is a function that's normally used when you want to reapeat a function however many times you want it too.
It is also used when you need to iterate over a specific range of numbers.
An example of a for loop: for(int i = startValue; i < endValue; i+ = someValue)
                          {
                            C.WL(body of for loop);
                          }
You can even have another for loop within a for loop and it looks like this: for(int i = startValue; i < endValue; i+ = someValue)
                                                                              {
                                                                                for(int j = startValue; j < endValue; j+ = someValue)
                                                                                {
                                                                                }
                                                                              }
Now, a while loop is used when you need tp repeat an action for an unknown numbers.
It can aslo be used to modify the control variable through non-standard increments.
And finally, it can be used to read a file.
An example of a while loop: int i = startValue;
                            while (i < endValue)
                            {
                              C.WL(body of the loop)
                              i += someValue;
                            }
