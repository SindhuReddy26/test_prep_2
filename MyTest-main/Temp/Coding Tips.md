## Different Patterns to categorise given coding question

**Sliding window**
  - Input: Linear DS( array, LL, String)
  - Asked to find the longest/shortest substring, subarray, or a desired value.
  - Ex: Maximum sum subarray of size ‘K’ (easy), Longest substring with ‘K’ distinct characters (medium), String anagrams (hard)
        
**Two Pointer**
  - Input: sorted arrays (or Linked Lists) and need to find a set of elements that fulfill certain constraints
  - The set of elements in the array is a pair, a triplet, or even a subarray
  - Ex: Squaring a sorted array (easy), Triplets that sum to zero (medium), Comparing strings that contain backspaces (medium)
     
**Fast and Slow pointers**
  - Input: The problem will deal with a loop in a linked list or array
  - When you need to know the position of a certain element or the overall length of the linked list.
  - Ex: Linked List Cycle (easy), Palindrome Linked List (medium), Cycle in a Circular Array (hard)
        
**Cyclic sort**
  - Input: Problems involving a sorted array with numbers in a given range
  - Ask to find the missing/duplicate/smallest number in an sorted/rotated array
  - Ex: Find the Missing Number (easy), Find the Smallest Missing Positive Number (medium)
        
**Merge Intervals**
  - Input: If you’re asked to produce a list with only mutually exclusive intervals
  - If you hear the term “overlapping intervals”.
  - Ex: Intervals Intersection (medium), Maximum CPU Load (hard)
        
**Solve In-place**
  - Swap corresponding values
  - Store one or more diff values in the same pointer
        
**In-place Reverse Linked List**
  - Input: Asked to reverse a linked list without using extra memory
  - Ex: Reverse a Sub-list (medium), Reverse every K-element Sub-list (medium)
        
**Backtracking**
  - Asked all permutation/combinations/subsets
  
**Subsets**
  - Use BFS/Backtracing approch for solution
  - Input: Problems where you need to find the combinations or permutations of a given set
  - Ex: Subsets With Duplicates (easy), String Permutations by changing case (medium)
  
**Stack**
- If recurssion is banned then use stack

**DFS**
  - Use recursion (or a stack for the iterative approach) to keep track of all the previous (parent) nodes while traversing.
  - Input: Given Tree/Graph. Asked to traverse a tree with in-order, preorder, or postorder DFS
  - If the problem requires searching for something where the node is closer to a leaf
  - Ex: Sum of Path Numbers (medium), All Paths for a Sum (medium)
        
**BFS**
  - Uses a queue to keep track of all the nodes of a level before jumping onto the next level
  - Traverse until queue is empty, for each head node it marks as visit and then add its child nodes into the queue.
  - Input: Given a tree/graph. Asked to traverse a tree in a level-by-level fashion (or level order traversal)
  _ Ex: Binary Tree Level Order Traversal (easy), Zigzag Traversal (medium)

**Heap**
  - Asked for top/least K items
  - Useful in situations like Priority Queue, Scheduling
  - Input: Asked to find the smallest/largest/median elements of a set
        -  Asked to find the top/smallest/frequent ‘K’ elements of a given set
        -  Asked to sort an array to find an exact element
  - Sometimes, useful in problems featuring a binary tree data structure
  - Ex: Top ‘K’ Numbers (easy), Top ‘K’ Frequent Numbers (medium)
  
**K-way Merge(use Heap concept to solve)**
  - Input: The problem will feature sorted arrays, lists, or a matrix
         - If the problem asks you to merge sorted lists, find the smallest element in a sorted list.
  - Ex: Merge K Sorted Lists (medium), K Pairs with Largest Sums (Hard)
        
**Binary Search**
  - middle = start + (end — start) / 2
  - Input: Given a sorted array, linked list, or matrix, asked to find a certain element
  - Ex: Order-agnostic Binary Search (easy), Search in a Sorted Infinite Array (medium)
        
**Topological Sort**
  - Input: The problem will deal with graphs that have no directed cycles
  - If you’re asked to update all objects in a sorted order
  - If you have a class of objects that follow a particular order
  - Ex: Task scheduling (medium), Minimum height of a tree (hard)

**Dynamic Programming**
  - If asked for maximum/minimum subarrays/subset/option/ stored previous calculated etc then use DP.
  
**Map/Trie**
  - If asked for common strings
  
**Map/Set for O(1) time & O(n) space**

**Sort input or O(nlongn) time and O(1) space**

## Coding Practise
- LeetCode : https://leetcode.com/discuss/general-discussion/460599/blind-75-leetcode-questions
- NeetCode 
- Grid 75 
    - https://www.techinterviewhandbook.org/best-practice-questions/
    - https://www.techinterviewhandbook.org/grind75?mode=preferences
    - https://www.techinterviewhandbook.org/coding-interview-study-plan/
- 14 Most used Patterns : https://hackernoon.com/14-patterns-to-ace-any-coding-interview-question-c5bb3357f6ed
- TakeUForward : https://takeuforward.org/interviews/strivers-sde-sheet-top-coding-interview-problems/
- Coding Ninja's : https://www.codingninjas.com/codestudio/problem-lists/striver-sde-sheet-problems
- Java2Blog: https : https://java2blog.com/java-coding-interview-questions/
