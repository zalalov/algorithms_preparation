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
