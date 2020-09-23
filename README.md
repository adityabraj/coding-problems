# coding-problems
Coding questions that I challenging.

Minimum addition

You are given an array A[] of N positive numbers. You are also given Q queries. Each query contains two integers l,r(l<=r) . For each query, determine the sum of all values that must be added to each number in range l to r such that bitwise AND of all numbers in the range is greater than 0.

You are required to minimize the total value that must be added. The value you must add to numbers is not necessarily equal for all numbers.

Note: Each query is independent of each other, that is, for each query, you must treat the range over the initial input array.

Input format

The first line contains an integer N denoting the number of array elements.
The next line denotes N array elements.
The next line contains a number Q denoting the number of queries.
Next Q lines contain two integers l and r.

Output format
For each query, print the minimum sum of values to be added in a new line.

Constraints
1 <= N <= 10^5
1 <= A[i] <= 10^9
1 <= Q <= 10^5
1 <= l <= r <= N

SAMPLE INPUT           
5                     
4 3 2 4 1         
4
1 4             
2 3
4 4
4 5

SAMPLE OUTPUT
3
0
0
1

Explanation:
For the first query we can add 1 to the 1st, 3rd and, 4th numbers.
For the second and third query, we don't need to add as the Bitwise AND is already > 0.
For the last query, we can add 1 to 4th number.

