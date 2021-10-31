
A repository to contribute solutions to some algorithmic questions.

## Guidelines

* Fork the repository.
* Clone your forked repository.
* Open the cloned repository in an IDE.
* Create a folder with your name.
* Solve and add any four questions from below in that folder.
* Make the pull request.

> Note: You can use any programming language for the submission. 
All The Best!!

## Questions

## Basic

1. Write a program to input a string and check if it is a palindrome or not.

```
Input: hannah
Output: String is palindrome
```

2. Write a program to input an array of integers and output the maximum element of the array.

```
Input: 1 2 3 4 5
Output: 5
```
3. Write a program to print the following pattern:

```
Output:

*
**
***
****
*****
```

4. Write a program to print the following pattern:

```
Output:

     *
    **
   ***
  ****
 *****
```

5. Given N  pairs of rectangles in the form of an array, where two successive elements of the arry denotes the length L and breadth B of the ith rectangle. 
The task is to return the maximum area out of all the rectangles.

INPUT:
N = 3 //number of rectangles
rect[] = {1,2,3,4,5,6} //dimensions of each succcessive rectangle

OUTPUT:
30

Explanation:
1. Total area of Rect. 1 = 1 * 2 = 2
2. Total area of Rect. 2 = 3 * 4 = 12
3. Total area of Rect. 3 = 5 * 6 = 30
4. Out of all rectangles, Rectangle 3 has the maximum area.

Input:
N = 2
rect[] = {12,3,40,5} 

Output:
200

Explanation:
1. Total area of Rect. 1 = 12 * 3 = 36
2. Total area of Rect. 2 = 40 * 5 = 200. 
3. Out of all rectangles, Rectangle 2 has the maximum area.



## Intermediate 

1. Find the Kth Maximum number in a given array in linear time complexity.
```
Input: arr = [1, 2, 4, 3, 5], k = 2
Output: 4

Input: arr = [1, 2, 2, 4, 4, 6, 5, 5], k = 3
Output: 5
```

2. Move all negative numbers to beginning and positive to end with constant 
extra space and linear time complexity.
```
Input: -12, 11, -13, -5, 6, -7, 5, -3, -6
Output: -12 -13 -5 -7 -3 -6 11 6 5
```

3. Given an array of integers ``nums`` and an integer ``target``, return indices of the two numbers such that they add up to ``target``.

```
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Output: Because nums[0] + nums[1] == 9, we return [0, 1].
```

4. Remove duplicates from a sorted array of positive numbers and return the remaining array, with the unique elements put towards the starting of the array, it doesn't matter what you put after the unique elements in the array.

```
Input: nums = [1,1,1,2,3,4]
Output: nums = [1,2,3,4,-1,-1]
```
