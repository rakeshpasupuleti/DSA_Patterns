# DSA Patterns

This section contains various Data Structures and Algorithms (DSA) patterns. Each pattern includes a brief description, tips on how to identify it, and some example problems that can be solved using that pattern.

## 1. Sliding Window

### Description
The Sliding Window pattern is used to perform a required operation on a specific window size of a given array or linked list, such as finding the longest subarray containing all 1s. Sliding Windows start from the 1st element and keep shifting right by one element and adjust the length of the window according to the problem that you are solving. In some cases, the window size remains constant and in other cases the sizes grows or shrinks.

### Tips to Identify the Pattern
- You are asked to find or calculate something within a contiguous subarray or sequence.
- The problem input is a linear data structure such as a linked list, array, or string.
- The problem might involve maximizing, minimizing, or finding a specific condition within a subarray.


### Example Problems
- **Longest Substring Without Repeating Characters**
- **Longest substring with ‘K’ distinct characters**
- **Maximum sum subarray of size ‘K’ **

---

## 2. Two Pointers

### Description
Two Pointers is a pattern where two pointers iterate through the data structure in tandem until one or both of the pointers hit a certain condition. This pattern is useful in situations where the input data is sorted or when you need to compare elements in a pair.

### Tips to Identify the Pattern
- Yt will feature problems where you deal with sorted arrays (or Linked Lists) and need to find a set of elements that fulfill certain constraints.
- The set of elements in the array is a pair, a triplet, or even a subarray
- The problem involves comparing elements in pairs.You need to move inward/outward from the edges of an array or list.

### Example Problems
- **Two Sum**
- **3Sum**
- **Triplets that sum to zero**

---

## 3. Fast and Slow Pointers (Tortoise and Hare)

### Description
The Fast and Slow Pointers pattern, also known as the Tortoise and Hare method, is used to detect cycles in linked lists or arrays. One pointer moves faster than the other, and if a cycle exists, they will eventually meet.

### Tips to Identify the Pattern
- You are asked to detect a cycle/loop in a linked list or an array.
- The problem involves finding the middle element of a linked list.
- The problem involves determining whether a linked list is a palindrome.

### Example Problems
- **Linked List Cycle**
- **Palindrome Linked List**
- **Cycle in a Circular Array**

---

## 4. Merge Intervals

### Description
The Merge Intervals pattern is used when you are given a list of intervals, and you need to merge overlapping intervals or find gaps between intervals. This pattern is useful in problems related to scheduling, meeting rooms, or time ranges.

### Tips to Identify the Pattern
- You are given a list of intervals.
- The problem involves merging or finding gaps between intervals.
- The intervals need to be processed or combined in some way.

### Example Problems
- ** Merge Intervals**
- **Insert Interval**
- **Meeting Rooms**

---

## 5. Cyclic Sort

### Description
The Cyclic Sort pattern is used to solve problems involving a list of numbers ranging from `1` to `n`. The pattern efficiently places each number in its correct position with minimal swaps.

### Tips to Identify the Pattern
- You are given an array containing numbers from `1` to `n`.
- The problem involves sorting or finding missing/duplicate numbers.
- The problem can be solved using cyclic swaps to place elements in their correct positions.

### Example Problems
- **Missing Number**
- **Find All Duplicates in an Array**
- **Find All Numbers Disappeared in an Array**

---

## 6. In-Place Reversal of Linked List

### Description
The In-Place Reversal of Linked List pattern is used to reverse a linked list, or a part of it, without using extra space. This pattern is common in problems that involve reversing the order of nodes in a linked list.

### Tips to Identify the Pattern
- You are asked to reverse a linked list or a part of it.
- The problem involves linked lists and in-place modifications.
- The problem can be solved by reversing pointers in the linked list.

### Example Problems
- ** Reverse Linked List**
- **Reverse Nodes in k-Group**

---

## 7. Tree BFS (Breadth-First Search)

### Description
This pattern is based on the Breadth First Search (BFS) technique to traverse a tree and uses a queue to keep track of all the nodes of a level before jumping onto the next level. Any problem involving the traversal of a tree in a level-by-level order can be efficiently solved using this approach.

### Tips to Identify the Pattern
- You are asked to traverse a tree or graph level by level.
- The problem involves finding the shortest path in an unweighted graph.
- The problem can be solved using a queue to explore nodes level by level.

### Example Problems
- ** Binary Tree Level Order Traversal**
- ** Binary Tree Zigzag Level Order Traversal**

---

## 8. Tree DFS (Depth-First Search)

### Description
The Tree DFS pattern is used to traverse a tree or graph by exploring as far as possible along each branch before backtracking. This pattern is useful in problems where you need to explore all possible paths or combinations.

### Tips to Identify the Pattern
- You are asked to explore all paths in a tree or graph.
- The problem involves finding all combinations or permutations.
- The problem can be solved using recursion or a stack to explore all branches.
- If you’re asked to traverse a tree with in-order, preorder, or postorder DFS.

### Example Problems
- **Maximum Depth of Binary Tree**
- **Path Sum**
- **Sum of Path Numbers**

---

## 9. Backtracking

### Description
The Backtracking pattern is used to solve problems where you need to explore all possible solutions. It involves choosing a path, exploring it, and backtracking if it doesn’t lead to a solution. This pattern is commonly used in problems related to permutations, combinations, and subsets.

### Tips to Identify the Pattern
- You are asked to generate all possible solutions or combinations.
- The problem involves constraints that need to be met.
- The problem can be solved by trying all possibilities and backtracking.

### Example Problems
- **Permutations**
- **Subsets**
- **Combination Sum**

---

## 10. Dynamic Programming

### Description
The Dynamic Programming (DP) pattern is used to solve problems where the solution can be broken down into overlapping subproblems. DP involves storing the results of subproblems to avoid redundant calculations and optimize the solution.

### Tips to Identify the Pattern
- The problem can be divided into smaller subproblems.
- The problem has optimal substructure and overlapping subproblems.
- The problem can be solved using a table to store subproblem results.

### Example Problems
- **Maximum Subarray**
- **Climbing Stairs**
- **Coin Change**

---

## 11. Topological Sort

### Description
Topological Sort is used to find a linear ordering of vertices in a directed acyclic graph (DAG) such that for every directed edge `uv` from vertex `u` to vertex `v`, `u` comes before `v` in the ordering. This pattern is often used in problems involving tasks, prerequisites, or dependencies.

### Tips to Identify the Pattern
- The problem involves tasks with dependencies or prerequisites.
- The input is a directed acyclic graph (DAG).
- The problem requires determining an order of execution.

### Example Problems
- **Course Schedule**
- **Course Schedule II**
- **Alien Dictionary**

---

## 12. Union Find (Disjoint Set)

### Description
The Union Find (or Disjoint Set) pattern is used to solve problems related to grouping or connecting elements. It efficiently manages and merges disjoint sets, making it useful in problems involving connected components, cycle detection, or determining if elements are in the same set.

### Tips to Identify the Pattern
- The problem involves connecting or grouping elements.
- The input consists of relationships or connections between elements.
- You need to determine if elements are in the same group or detect cycles in a graph.

### Example Problems
- **Number of Connected Components in an Undirected Graph**
- **Redundant Connection**
- **Number of Provinces**

---

## 13. Binary Search/ Modified Binary Search

### Description
The Binary Search pattern is used to efficiently find an element or determine if an element exists in a sorted array. The pattern repeatedly divides the search space in half, reducing the time complexity to O(log n).

### Tips to Identify the Pattern
- The problem involves searching in a sorted array or list.
- You need to find an element or the position of an element.
- The problem can be solved by repeatedly dividing the search space in half.

### Example Problems
- **Binary Search**
- **Search in Rotated Sorted Array**
- **Search a Search a 2D Matrix**

---

## 14. Greedy

### Description
The Greedy pattern is used to solve optimization problems where the locally optimal choice leads to a globally optimal solution. This pattern is useful in problems involving finding the maximum or minimum value.

### Tips to Identify the Pattern
- The problem involves making choices to maximize or minimize a value.
- The input can be processed in a sequential manner.
- The problem can be solved by making the best choice at each step.

### Example Problems
- **Jump Game**
- **Jump Game II**
- **Non-overlapping Intervals**

---

## 15. Bit Manipulation

### Description
The Bit Manipulation pattern involves solving problems by directly manipulating the bits of numbers. This pattern is efficient for problems related to binary representations, XOR operations, or finding unique elements in a list.

### Tips to Identify the Pattern
- The problem involves binary numbers or operations.
- You need to optimize the solution by using bitwise operations.
- The problem can be solved by manipulating bits directly.

### Example Problems
- **Single Number**
- **Counting Bits**
- **Number of 1 Bits**

---
## 16. Top K Elements

### Description
The Top K Elements pattern is used to find the top K largest or smallest elements in a collection, such as an array or a list. This pattern is commonly solved using a heap (priority queue) or by sorting the array.

### Tips to Identify the Pattern
- You are asked to find the K largest or smallest elements in an array.
- The problem involves ranking or ordering elements based on their values.
- The problem can be solved by maintaining a heap of size K or sorting the array.

### Example Problems
- **Top K Frequent Elements**
- **Kth Largest Element in an Array**
- **K Closest Points to Origin**

---

## 17. K-Way Merging

### Description
The K-Way Merging pattern is used to merge multiple sorted arrays or lists into one sorted array. This pattern is often used in problems that involve combining or merging multiple data streams or lists.

### Tips to Identify the Pattern
- You are given multiple sorted arrays or lists and asked to merge them into one sorted list.
- The problem involves combining sorted sequences.
- The problem can be solved by maintaining a min-heap to keep track of the smallest elements from each array.

### Example Problems
- **Merge k Sorted Lists**
- **Find K Pairs with Smallest Sums**
- **Kth Smallest Element in a Sorted Matrix**

---

## 18. Two Heaps

### Description
The Two Heaps pattern is used to solve problems where you need to find the median or any other specific percentile in a data stream. It involves using two heaps: a max-heap to store the smaller half of the elements and a min-heap to store the larger half.

### Tips to Identify the Pattern
- The problem involves finding the median or another percentile in a stream of numbers.
- The problem requires dynamically adjusting to new data while maintaining a balance between two halves.
- The problem can be solved by using two heaps to store the lower and upper halves of the data.

### Example Problems
- **Find Median from Data Stream**
- **Sliding Window Median**
- **Sliding Window Maximum** (can be adapted)

---

## 19. Prefix and Postfix Computations

### Description
The Prefix and Postfix Computations pattern involves calculating prefix (cumulative) and postfix (suffix) values for an array. This pattern is often used in problems where you need to compute results for each element based on all other elements in the array without directly iterating over all other elements for each computation.

### Tips to Identify the Pattern
- The problem involves operations where each element's result depends on all other elements in the array.
- You are asked to calculate cumulative products, sums, or other values while excluding the current element.
- The problem can be solved by precomputing prefix and postfix arrays to avoid redundant calculations.

### Example Problems
- **Product of Array Except Self**
- **Subarray Sum Equals K**
- **Count Number of Nice Subarrays**

---

# Quick Ref

**Big-O notations** indicate the algorithm’s general time complexity  
`n` indicates the total number of elements in the input

## Maximum Continuous Subarray
- **Sliding Window:** `O(n)`

## Input Array is Sorted
- **Binary Search:** `O(log n)`
- **Two Pointers:** `O(n)`

## Input is a Binary Tree
- **DFS (Preorder, Inorder, Postorder):** `O(n)`
- **BFS (Level Order):** `O(n)`

## Input is a Binary Search Tree
- **Left < Cur < Right:** `O(log n)`
- **Inorder Traversal visits the nodes in ascending (sorted) order:** `O(n)`

## Input is a Matrix/Graph
- **DFS (Recursion, Stack):** `O(n)`
- **BFS (Queue):** `O(n)`

## Find the Shortest/Nearest Path/Distance in a Tree/Matrix/Graph
- **BFS (non-weighted):** `O(n)`
- **Dijkstra (weighted):** `O(E log V)`

## String Concatenation
- **StringBuilder:** `O(n)` (Java, C#, etc.)
- **String.join():** `O(n)` (Python)

## Input is a Linked List
- **Dummy Node**
- **Two Pointers:** `O(n)`
- **Fast & Slow Pointers:** `O(n)`

## Recomputing the Same Input
- **Memoization**

## Recursion is Banned
- **Stack**

## Permutations/Combinations/Subsets
- **Backtracking**

## Find the Top/Least Kth element
- **QuickSelect:** `O(n)` average, `O(n²)` worst
- **Heap:** `O(n log k)`

## Common Strings
- **Map**
- **Trie**

## Sort
- **Quick Sort:** `O(n log n)` average, `O(n²)` worst
- **Merge Sort:** `O(n log n)`
- **Built-in sorts:** `O(n log n)`

## Find the Smallest/Largest/Median in a Stream
- **Two Heaps**

## Must Solve In-Place
- **Swap corresponding values**
- **Store different values in the same pointer**

## Maximum/Minimum Subarray/Subset/Options
- **Dynamic Programming**

## Map/Set
- **Time:** `O(1)`
- **Space:** `O(n)`

## Deque
- **Replaces Stack, Queue, and LinkedList**



