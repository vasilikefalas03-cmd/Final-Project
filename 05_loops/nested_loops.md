You can even have another for loop within a for loop, it's called a nested loop and it looks like this: 
for(int i = startValue; i < endValue; i+ = someValue) outer loop
{
  for(int j = startValue;< endValue; j+ = someValue) inner loop
  {
    C.WL(j);
  }
  C.WL(i);
}
You would normally use a nested loop when you need to find two different variables at the same time.
