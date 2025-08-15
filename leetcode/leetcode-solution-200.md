# leetcode solution 200

## Section 1: Introduction

This article selects about 200 questions from Leetcode, removing some complicated questions that do not have much algorithmic thinking, while retaining classic questions that are often asked in interviews.

https://github.com/CyC2018/CS-Notes/blob/master/notes/Leetcode%20%E9%A2%98%E8%A7%A3%20-%20%E6%95%B0%E7%BB%84%E4%B8%8E%E7%9F%A9%E9%98%B5.md

### Algorithm Concepts
- Two Pointers
- Sorting
- Greedy Approach
- Binary Search
- Divide and Conquer
- Search
- Dynamic Programming
- Mathematics

## Data Structures
- Linked List
- Tree
- Stack and Queue
- Hash Table
- String
- Array and Matrix
  - 283\. Move Zeroes (Easy)

[Leetcode](https://leetcode.com/problems/move-zeroes/description/) / [力扣](https://leetcode-cn.com/problems/move-zeroes/description/)

```html
For example, given nums = [0, 1, 0, 3, 12], after calling your function, nums should be [1, 3, 12, 0, 0].
```

```java
public void moveZeroes(int[] nums) {
    int idx = 0;
    for (int num : nums) {
        if (num != 0) {
            nums[idx++] = num;
        }
    }
    while (idx < nums.length) {
        nums[idx++] = 0;
    }
}
```
Use Case: Sparse Data in Arrays
Imagine you are working with sensor readings collected in real time. Some readings might be 0 because the sensor didn’t detect anything. You want to process only the actual measurements efficiently while keeping the dataset size the same.

- Graph
- Bit Manipulation





