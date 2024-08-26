# DSA Patterns

This section contains various Data Structures and Algorithms (DSA) patterns. Each pattern includes a brief description, tips on how to identify it, and some example problems that can be solved using that pattern.

## 1. Sliding Window

### Description
The Sliding Window pattern is used to solve problems that involve arrays or lists of data where you need to find a subarray or a contiguous sequence. The window size can be fixed or variable, and you slide the window over the array to find the desired result.

### Tips to Identify the Pattern
- You are asked to find or calculate something within a contiguous subarray or sequence.
- The problem involves arrays or lists.
- The problem might involve maximizing, minimizing, or finding a specific condition within a subarray.

### Example Problems
- **LeetCode 3: Longest Substring Without Repeating Characters**
- **LeetCode 567: Permutation in String**
- **LeetCode 209: Minimum Size Subarray Sum**

---

## 2. Two Pointers

### Description
The Two Pointers pattern is used to solve problems where you need to process elements in an array or a list from both ends towards the middle, or from one end using two pointers. This pattern is useful in situations where the input data is sorted or when you need to compare elements in a pair.

### Tips to Identify the Pattern
- You are asked to find pairs in a sorted array.
- The problem involves comparing elements in pairs.
- You need to move inward/outward from the edges of an array or list.

### Example Problems
- **LeetCode 1: Two Sum**
- **LeetCode 15: 3Sum**
- **LeetCode 167: Two Sum II - Input Array Is Sorted**

---

## 3. Fast and Slow Pointers (Tortoise and Hare)

### Description
The Fast and Slow Pointers pattern, also known as the Tortoise and Hare method, is used to detect cycles in linked lists or arrays. One pointer moves faster than the other, and if a cycle exists, they will eventually meet.

### Tips to Identify the Pattern
- You are asked to detect a cycle in a linked list or an array.
- The problem involves finding the middle element of a linked list.
- The problem involves determining whether a linked list is a palindrome.

### Example Problems
- **LeetCode 141: Linked List Cycle**
- **LeetCode 142: Linked List Cycle II**
- **LeetCode 234: Palindrome Linked List**

---

## 4. Merge Intervals

### Description
The Merge Intervals pattern is used when you are given a list of intervals, and you need to merge overlapping intervals or find gaps between intervals. This pattern is useful in problems related to scheduling, meeting rooms, or time ranges.

### Tips to Identify the Pattern
- You are given a list of intervals.
- The problem involves merging or finding gaps between intervals.
- The intervals need to be processed or combined in some way.

### Example Problems
- **LeetCode 56: Merge Intervals**
- **LeetCode 57: Insert Interval**
- **LeetCode 252: Meeting Rooms**

---

## 5. Cyclic Sort

### Description
The Cyclic Sort pattern is used to solve problems involving a list of numbers ranging from `1` to `n`. The pattern efficiently places each number in its correct position with minimal swaps.

### Tips to Identify the Pattern
- You are given an array containing numbers from `1` to `n`.
- The problem involves sorting or finding missing/duplicate numbers.
- The problem can be solved using cyclic swaps to place elements in their correct positions.

### Example Problems
- **LeetCode 268: Missing Number**
- **LeetCode 442: Find All Duplicates in an Array**
- **LeetCode 448: Find All Numbers Disappeared in an Array**

---

## 6. In-Place Reversal of Linked List

### Description
The In-Place Reversal of Linked List pattern is used to reverse a linked list, or a part of it, without using extra space. This pattern is common in problems that involve reversing the order of nodes in a linked list.

### Tips to Identify the Pattern
- You are asked to reverse a linked list or a part of it.
- The problem involves linked lists and in-place modifications.
- The problem can be solved by reversing pointers in the linked list.

### Example Problems
- **LeetCode 206: Reverse Linked List**
- **LeetCode 92: Reverse Linked List II**
- **LeetCode 25: Reverse Nodes in k-Group**

---

## 7. Tree BFS (Breadth-First Search)

### Description
The Tree BFS pattern is used to traverse a tree level by level, starting from the root. This pattern is useful in problems where you need to explore nodes in a tree in a breadth-first manner.

### Tips to Identify the Pattern
- You are asked to traverse a tree or graph level by level.
- The problem involves finding the shortest path in an unweighted graph.
- The problem can be solved using a queue to explore nodes level by level.

### Example Problems
- **LeetCode 102: Binary Tree Level Order Traversal**
- **LeetCode 107: Binary Tree Level Order Traversal II**
- **LeetCode 103: Binary Tree Zigzag Level Order Traversal**

---

## 8. Tree DFS (Depth-First Search)

### Description
The Tree DFS pattern is used to traverse a tree or graph by exploring as far as possible along each branch before backtracking. This pattern is useful in problems where you need to explore all possible paths or combinations.

### Tips to Identify the Pattern
- You are asked to explore all paths in a tree or graph.
- The problem involves finding all combinations or permutations.
- The problem can be solved using recursion or a stack to explore all branches.

### Example Problems
- **LeetCode 104: Maximum Depth of Binary Tree**
- **LeetCode 112: Path Sum**
- **LeetCode 113: Path Sum II**

---

## 9. Backtracking

### Description
The Backtracking pattern is used to solve problems where you need to explore all possible solutions. It involves choosing a path, exploring it, and backtracking if it doesn’t lead to a solution. This pattern is commonly used in problems related to permutations, combinations, and subsets.

### Tips to Identify the Pattern
- You are asked to generate all possible solutions or combinations.
- The problem involves constraints that need to be met.
- The problem can be solved by trying all possibilities and backtracking.

### Example Problems
- **LeetCode 46: Permutations**
- **LeetCode 78: Subsets**
- **LeetCode 39: Combination Sum**

---

## 10. Dynamic Programming

### Description
The Dynamic Programming (DP) pattern is used to solve problems where the solution can be broken down into overlapping subproblems. DP involves storing the results of subproblems to avoid redundant calculations and optimize the solution.

### Tips to Identify the Pattern
- The problem can be divided into smaller subproblems.
- The problem has optimal substructure and overlapping subproblems.
- The problem can be solved using a table to store subproblem results.

### Example Problems
- **LeetCode 53: Maximum Subarray**
- **LeetCode 70: Climbing Stairs**
- **LeetCode 322: Coin Change**

---

## 11. Topological Sort

### Description
Topological Sort is used to find a linear ordering of vertices in a directed acyclic graph (DAG) such that for every directed edge `uv` from vertex `u` to vertex `v`, `u` comes before `v` in the ordering. This pattern is often used in problems involving tasks, prerequisites, or dependencies.

### Tips to Identify the Pattern
- The problem involves tasks with dependencies or prerequisites.
- The input is a directed acyclic graph (DAG).
- The problem requires determining an order of execution.

### Example Problems
- **LeetCode 207: Course Schedule**
- **LeetCode 210: Course Schedule II**
- **LeetCode 269: Alien Dictionary**

---

## 12. Union Find (Disjoint Set)

### Description
The Union Find (or Disjoint Set) pattern is used to solve problems related to grouping or connecting elements. It efficiently manages and merges disjoint sets, making it useful in problems involving connected components, cycle detection, or determining if elements are in the same set.

### Tips to Identify the Pattern
- The problem involves connecting or grouping elements.
- The input consists of relationships or connections between elements.
- You need to determine if elements are in the same group or detect cycles in a graph.

### Example Problems
- **LeetCode 323: Number of Connected Components in an Undirected Graph**
- **LeetCode 684: Redundant Connection**
- **LeetCode 547: Number of Provinces**

---

## 13. Binary Search

### Description
The Binary Search pattern is used to efficiently find an element or determine if an element exists in a sorted array. The pattern repeatedly divides the search space in half, reducing the time complexity to O(log n).

### Tips to Identify the Pattern
- The problem involves searching in a sorted array or list.
- You need to find an element or the position of an element.
- The problem can be solved by repeatedly dividing the search space in half.

### Example Problems
- **LeetCode 704: Binary Search**
- **LeetCode 33: Search in Rotated Sorted Array**
- **LeetCode 74: Search a
