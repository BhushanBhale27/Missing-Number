# Missing-Number

You are given an array Containing n-1 distinct numbers from range [1, n].

There is one element missing from the range[1,n] in the array. Find that missing Number and return it.



Solve it without using any extra array.



Example 1:

Input: nums = [3,4,1]

Output: 2

Explanation: n = 3 since there are 3 numbers, so all numbers are in the range [1,3]. 2 is the missing number in the range since it does not appear in nums.



Example 2:

Input: nums = [2,1]

Output: 3

Explanation: n = 2 since there are 2 numbers, so all numbers are in the range [1,2]. 2 is the missing number in the range since it does not appear in nums.



Example 3:

Input: nums = [9,6,4,2,3,5,7,1]

Output: 8

Explanation: n = 9 since there are 9 numbers, so all numbers are in the range [1,9]. 8 is the missing number in the range since it does not appear in nums.



Constraints:

n == nums.length
1 <= n <= 104
0 <= nums[i] <= n
All the numbers of nums are unique.
