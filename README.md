# DAY-22
Lexographically Smallest String After a Swap (LC-406)

Problem Stament 

Given a string s containing only digits, return the lexicographically smallest string that can be obtained after swapping adjacent digits in s with the same parity at most once.Digits have the same parity if both are odd or both are even. For example, 5 and 9, as well as 2 and 4, have the same parity, while 6 and 9 do not.

 
Example 1:

Input: s = "45320"

Output: "43520"

Explanation:

s[1] == '5' and s[2] == '3' both have the same parity, and swapping them results in the lexicographically smallest string.

Solution Approach 

Have looped through the string & checked for parity of even or odd & if current element is greater than next element have swapped & breaked through for loop.
