A do-while is normally neede when you want to execute a set of instructions at least once before checking a condition.
It's also needed when you want to validate a user's input and even when you want to repeat the function.
An example of a do-while: int num;
                          bool validInput;
                          do
                          {
                            C.WL("Enter a number between 1 and 7"); prompting with a constraint
                            num = Convert.ToInt32(Console.ReadLine()); reading it in, assuming it's the right conversion type
                            validInput = num >= 1 && num <= 7; checking if it's valid
                          } while (validInput == false); set the cdt accordingly
Another example of a do-while with a char ans: char ans;
                                      do
                                      {
                                        C.WL("Would you like to play again? (y/n)");
                                        ans = Convert.ToChar(Console.ReadLine());
                                      } while (ans == 'y');
