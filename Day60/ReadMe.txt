Task
Given set S={1,2,3,...,N}. Find two integers, A and B (where A<B), from set S such that the value of A&B is the maximum possible and also less than a given integer, K.
In this case, & represents the bitwise AND operator.

Function Description
Complete the bitwiseAnd function in the editor below.
bitwiseAnd has the following paramter(s):
- int N: the maximum integer to consider
- int K: the limit of the result, inclusive

Input Format
The first line contains an integer, T, the number of test cases.
Each of the T subsequent lines defines a test case as 2 space-separated integers, N and K, respectively.

Sample Input

STDIN   Function
-----   --------
3       T = 3
5 2     N = 5, K = 2
8 5     N = 8, K = 5
2 2     N = 8, K = 5

Sample Output

1
4
0
