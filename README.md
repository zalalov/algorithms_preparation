# Algorithms Getting Started
## 1. Given a string s, return the longest palindromic substring in s.

### Example 1:
```
Input: s = "babad"
Output: "bab"
Note: "aba" is also a valid answer.

```
### Example 2:
```
Input: s = "cbbd"
Output: "bb"
```

### Example 3:
```
Input: s = "a"
Output: "a"
```
### Example 4:
```
Input: s = "ac"
Output: "a"
```

## 2.Given the heads of two singly linked-lists headA and headB, return the node at which the two lists intersect. If the two linked lists have no intersection at all, return null.

For example, the following two linked lists begin to intersect at node c1:

![image](https://user-images.githubusercontent.com/15165282/116077961-58cbf980-a696-11eb-9d62-3c3b3ae3a06c.png)

It is guaranteed that there are no cycles anywhere in the entire linked structure.

Note that the linked lists must retain their original structure after the function returns.

### Example:
![image](https://user-images.githubusercontent.com/15165282/116078085-7b5e1280-a696-11eb-8959-f341e54b7239.png)

```
Input: intersectVal = 8, listA = [4,1,8,4,5], listB = [5,6,1,8,4,5], skipA = 2, skipB = 3
Output: Intersected at '8'
Explanation: The intersected node's value is 8 (note that this must not be 0 if the two lists intersect).
From the head of A, it reads as [4,1,8,4,5]. From the head of B, it reads as [5,6,1,8,4,5]. There are 2 nodes before the intersected node in A; There are 3 nodes before the intersected node in B.
```

## 3. Given the root of a binary search tree, and an integer k, return the kth (1-indexed) smallest element in the tree.

### Example:
![image](https://user-images.githubusercontent.com/15165282/116079292-ea883680-a697-11eb-93d9-3a848c6bfc6f.png)

```
Input: root = [5,3,6,2,4,null,null,1], k = 3
Output: 3
```

## 4.Given an array of intervals where intervals[i] = [starti, endi], merge all overlapping intervals, and return an array of the non-overlapping intervals that cover all the intervals in the input.

### Example:
```
Input: intervals = [[1,3],[2,6],[8,10],[15,18]]
Output: [[1,6],[8,10],[15,18]]
Explanation: Since intervals [1,3] and [2,6] overlaps, merge them into [1,6].
```

## 5. Find Peak Element

Given an integer array nums, find a peak element, and return its index. If the array contains multiple peaks, return the index to any of the peaks.

You may imagine that nums[-1] = nums[n] = -∞.

### Example:
```
Input: nums = [1,2,3,1]
Output: 2
Explanation: 3 is a peak element and your function should return the index number 2.
```

## 6. Strong Password
A password is considered strong if the below conditions are all met:

It has at least 6 characters and at most 20 characters.
It contains at least one lowercase letter, at least one uppercase letter, and at least one digit.
It does not contain three repeating characters in a row (i.e., "...aaa..." is weak, but "...aa...a..." is strong, assuming other conditions are met).

Given a string password, return the minimum number of steps required to make password strong. if password is already strong, return 0.

In one step, you can:

Insert one character to password,
Delete one character from password, or
Replace one character of password with another character.
 

### Example 1:
```
Input: password = "a"
Output: 5
```

### Example 2:
```
Input: password = "aA1"
Output: 3
```

### Example 3:
```
Input: password = "1337C0d3"
Output: 0
```

## 7.Number of Digit One
Given an integer n, count the total number of digit 1 appearing in all non-negative integers less than or equal to n.

### Example 1:
```
Input: n = 13
Output: 6
```
### Example 2:
```
Input: n = 0
Output: 0
```
## 8. Heaters
Winter is coming! During the contest, your first job is to design a standard heater with a fixed warm radius to warm all the houses.

Every house can be warmed, as long as the house is within the heater's warm radius range. 

Given the positions of houses and heaters on a horizontal line, return the minimum radius standard of heaters so that those heaters could cover all houses.

Notice that all the heaters follow your radius standard, and the warm radius will the same.

 

### Example 1:
```
Input: houses = [1,2,3], heaters = [2]
Output: 1
Explanation: The only heater was placed in the position 2, and if we use the radius 1 standard, then all the houses can be warmed.
```
### Example 2:
```
Input: houses = [1,2,3,4], heaters = [1,4]
Output: 1
Explanation: The two heater was placed in the position 1 and 4. We need to use radius 1 standard, then all the houses can be warmed.
```
### Example 3:
```
Input: houses = [1,5], heaters = [2]
Output: 3
```
