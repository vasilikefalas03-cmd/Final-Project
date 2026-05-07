A switch statement is normally used to execute certain functions, granted that you give the correct instructions, such as the number and the operator.
An example of a switch looks like this: switch(variable)
                                        {
                                            case 0:
                                                  instructions here
                                                  break;
                                                  other cases here
                                                  possibly default case
                                        }
A nested switch statement is when you have multiple switches in a single loop to do different things.
An example of one would look like this: switch(variable)
                                        {
                                            case 0:
                                              switch(variable)
                                              {
                                                  case 0:
                                                    instuctions here
                                                    break;
                                                    other cases
                                                    posible default case
                                              }
                                              break;
                                            case 0:
                                              switch(variable)
                                              {
                                                case 0:
                                                  instructions here
                                                  break;
                                                  other cases
                                                  possible default case
                                              }
                                         }
