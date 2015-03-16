DynamicArray
============

Implemented a dynamic array that holds integer values and that grows when necessary to make room for new elements. Similar to ArrayList in Java.


function to add an element to the end of the array.
function to remove an element from any position in the array. 

The initial size of the array is less than or equal to 4.

Note: All input must be read from the standard input stream, and all output must be written to the
standard output stream.




Input: The input begins with the number t of test cases in a single line (t  100). Each of the next t
lines starts with a number n (1  n  1000000) followed by a list of n operations. There are two types
of operations: append, and delete. An append operation is represented a letter ‘a’ followed by a number m
(1  m  1000000) to append. A delete operation is represented by a letter ‘d’ followed by the index i of
the element to remove (0  i  array size − 1).


Output: For each test case output the elements of the array after all the operations have been performed.
Consecutive elements should be separated by a single space.


Example:
Input:
3
4 a 5 a 0 a 6 a 0
6 a 3 a 0 a 6 a 5 d 0 a 0
8 a 1 a 2 a 3 a 4 d 1 a 5 a 6 d 2
1
Output:
5 0 6 0
5 0 6 0
1 4 6 5


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/vishalshar/dynamicarray/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

