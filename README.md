# C-3: Data Structures

## Exercise 3.1
>(a) Does the `==` operator correctly test for equality between strings?
>(b) Since arrays of `chars` and `char*` pointers act similarly, can we test equality by using a line like
`if(*C == *D)`? Test in CodeAnywhere/Repl to verify your answers.

## Exercise 3.2
>Make a `compare.c` file in your repository and complete a `compare()`
function to evaluate whether two strings are equal.
To do this, you will need to step through each string comparing characters, until you
reach the string termination character. Be sure your code works for all the tested cases above,
plus any others that might be important.

## Exercise 3.3
>Implement the above in `arrayExample.c`

## Exercise 3.4
> Describe where in the memory diagrams the strings will be stored (you may need to look back
to a prior module). Why can't the string data be stored on the stack?

## Exercise 3.5
> Implement the above in `arrayExample2.c`

## Exercise 3.6
> Implement the above in   `arrayExample3.c`, completing the code in   `main()`,
and including the struct definition and the `print()` method.

## Exercise 3.7
> Add code to your `arrayExample3.c` to print the start address of each heap block, and include that in a memory diagram below. You do not need to list addresses on the stack or globals area.

**Stack:**

|Name | Contents |
| :---  |:--- |
|        |         |
|        |         |

**Globals:**

|Name | Contents |
| :---  |:--- |
|        |         |
|        |         |

**Heap:**

| Address  |  Contents |
| :--- |:--- |
|          |        |
|          |        |
|          |        |


## Exercise 3.8
> Implement the above in `linkedlistExample.c`, including a complete `printList()` function, and fill in a complete memory diagram right after the three nodes are to the list (only include heap addresses - use the debugger to find them).


**Stack:**

|Name | Contents |
| :---  |:--- |
|        |         |
|        |         |

**Globals:**

|Name | Contents |
| :---  |:--- |
|        |         |
|        |         |

**Heap:**

| Address  |  Contents |
| :--- |:--- |
|          |        |
|          |        |
|          |        |

## Exercise 3.9
> Implement the above in `linkedlistExample2.c`, completing the required methods. For the moment, the `copy()` method can remain not implemented.


## Exercise 3.10
> Implement the `copy()` method, ensuring that a deep copy is made, so that every person struct is duplicated. Un-comment the block comments in `main()`. Add all this code to `linkedlistExample2.c`.

## Exercise 3.11
> Implement the needed code in various methods in `linkedlistTable.c` to make this idea work. You have seen this data structure before. What is it called? Draw a memory diagram after the first three insertions. You can either use a markdown table, or draw on paper and add a photo to your README file.
