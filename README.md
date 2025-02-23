, print the array after each iteration of the insertion sort, i.e., whenever the next element has been inserted at its correct position. Since the array composed of just the first element is already sorted, begin printing after placing the second element.

Example.



Working from left to right, we get the following output:

3 4 7 5 6 2 1
3 4 7 5 6 2 1
3 4 5 7 6 2 1
3 4 5 6 7 2 1
2 3 4 5 6 7 1
1 2 3 4 5 6 7
Function Description

Complete the insertionSort2 function in the editor below.

insertionSort2 has the following parameter(s):

int n: the length of 
int arr[n]: an array of integers
Prints

At each iteration, print the array as space-separated integers on its own line.

Input Format

The first line contains an integer, , the size of .
The next line contains  space-separated integers .

Constraints



Output Format

Print the entire array on a new line at every iteration.

Sample Input

STDIN           Function
-----           --------
6               n = 6
1 4 3 5 6 2     arr = [1, 4, 3, 5, 6, 2]
Sample Output

1 4 3 5 6 2 
1 3 4 5 6 2 
1 3 4 5 6 2 
1 3 4 5 6 2 
1 2 3 4 5 6 


