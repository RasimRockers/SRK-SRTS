## ✅ **Topic: Arrays (1–15)**

### 1. **What is the time complexity to find the maximum element in an unsorted array?**

**A)** O(log n)

**B)** O(n log n)

**C)** O(n) ✅

**D)** O(1)

**Explanation:**
You must traverse the entire array once to find the maximum value, so the time complexity is O(n).

---

### 2. **Which algorithm is best for finding the maximum sum subarray?**

**A)** Merge Sort

**B)** Kadane's Algorithm ✅

**C)** DFS

**D)** Quick Sort

**Explanation:**
Kadane's Algorithm solves the maximum subarray sum problem in O(n) time using dynamic programming.

---

### 3. **Which sorting algorithm has the best average case time complexity?**


**A)** Bubble Sort

**B)** Selection Sort

**C)** Merge Sort ✅

**D)** Insertion Sort

**Explanation:**
Merge Sort has an average case time complexity of O(n log n), which is better than O(n²) of Bubble, Selection, and Insertion.

---

### 4. **What is the auxiliary space for Merge Sort?**

**A)** O(1)

**B)** O(n) ✅

**C)** O(log n)

**D)** O(n log n)

**Explanation:**
Merge sort uses O(n) extra space for the temporary arrays used in the merging process.

---

### 5. **Which algorithm efficiently sorts an array of 0s, 1s, and 2s?**

**A)** Merge Sort

**B)** Dutch National Flag ✅

**C)** Insertion Sort

**D)** Heap Sort

**Explanation:**
Dutch National Flag algorithm sorts the array in a single pass using three pointers – best for arrays with limited values.

---

### 6. **What is the time complexity of Binary Search?**

**A)** O(n)

**B)** O(n log n)

**C)** O(log n) ✅

**D)** O(1)

**Explanation:**
Binary Search divides the search space in half each time, so time complexity is O(log n).

---

### 7. **How many swaps in the best case for Bubble Sort (already sorted array)?**

**A)** n

**B)** 0 ✅

**C)** n log n

**D)** n²

**Explanation:**
In the best case, no swaps are needed because the array is already sorted.

---

### 8. **Which data structure is used for Quick Sort recursion?**

**A)** Stack ✅

**B)** Queue

**C)** Linked List

**D)** Tree

**Explanation:**
Quick Sort uses recursion internally, and recursion uses the call stack.

---

### 9. **Which sorting algorithm is NOT in-place?**

**A)** Merge Sort ✅

**B)** Bubble Sort

**C)** Insertion Sort

**D)** Quick Sort

**Explanation:**
Merge Sort requires additional space to store merged arrays, so it's not in-place.

---

### 10. **Which technique is used in Merge Sort?**

**A)** Divide and Conquer ✅

**B)** Greedy

**C)** Backtracking

**D)** Dynamic Programming

**Explanation:**
Merge Sort divides the array into halves recursively, sorts, and merges them – classic divide and conquer.

---

### 11. **Which data structure allows random access?**

**A)** Stack

**B)** Queue

**C)** Array ✅

**D)** Linked List

**Explanation:**
Arrays allow O(1) access by index, unlike Linked Lists which require traversal.

---

### 12. **Which of the following is an advantage of arrays?**

**A)** Dynamic size

**B)** Ease of insertion

**C)** Random access ✅

**D)** Fast deletion

**Explanation:**
Arrays support O(1) random access, which is an advantage over most dynamic structures.

---

### 13. **How many comparisons are needed in linear search (worst case)?**

**A)** O(1)

**B)** O(log n)

**C)** O(n) ✅

**D)** O(n²)

**Explanation:**
In the worst case, linear search checks all `n` elements, so it’s O(n).

---

### 14. **What is the most efficient way to remove duplicates from a sorted array?**

**A)** Hash Map

**B)** Two-pointer technique ✅

**C)** Stack

**D)** Heap

**Explanation:**
In a sorted array, duplicates are adjacent. Use two pointers to overwrite duplicates.

---

### 15. **In a rotated sorted array, which algorithm is used to find an element efficiently?**

**A)** Linear Search

**B)** Binary Search ✅

**C)** DFS

**D)** BFS

**Explanation:**
A modified binary search can find an element in O(log n) time in a rotated sorted array.

---

## ✅ **Topic: Strings (16–30)**

---

### 16. **Which is the fastest algorithm to search a pattern in a string?**

**A)** Brute Force

**B)** DFS

**C)** BFS

**D)** KMP ✅

**Explanation:**
KMP (Knuth-Morris-Pratt) uses preprocessing to avoid unnecessary rechecking, giving it a linear time complexity: O(n + m).

---

### 17. **Which of the following is a palindrome?**

**A)** hello

**B)** radar ✅

**C)** apple

**D)** tree

**Explanation:**
"radar" reads the same forwards and backwards — it is a palindrome.

---

### 18. **Time complexity of checking if two strings are anagrams (by sorting)?**

**A)** O(n log n) ✅

**B)** O(n²)

**C)** O(1)

**D)** O(n³)

**Explanation:**
Sorting two strings and comparing takes O(n log n) time. Alternate: O(n) using counting (hash map or array).

---

### 19. **Which function returns length of a string in C?**

**A)** strlength()

**B)** stringlength()

**C)** strlen() ✅

**D)** strsize()

**Explanation:**
`strlen()` from `<string.h>` returns the number of characters before the null terminator.

---

### 20. **What does "abc" + "def" result in most programming languages (like Python/Java)?**

**A)** Error

**B)** abcdef ✅

**C)** defabc

**D)** cba

**Explanation:**
String concatenation results in `"abcdef"` in most high-level languages.

---

### 21. **Which data structure is best for reversing a string?**

**A)** Queue

**B)** Stack ✅

**C)** Tree

**D)** Linked List


**Explanation:**
Stack follows LIFO order — pushing and popping characters naturally reverses the string.

---

### 22. **How to check if one string is a rotation of another?**

**A)** Use hash table

**B)** Sort and compare

**C)** Check if s2 in (s1+s1) ✅

**D)** Use stack

**Explanation:**
If s2 is a rotation of s1, then it must be a substring of `s1+s1`.

---

### 23. **What is the time complexity to compare two strings of length n?**

**A)** O(1)

**B)** O(log n)

**C)** O(n) ✅

**D)** O(n²)

**Explanation:**
You need to compare each character of both strings — O(n) time.

---

### 24. **Which of the following is not a valid string operation in most languages?**

**A)** Concatenation

**B)** Substring

**C)** Deletion by index ✅

**D)** Indexing

**Explanation:**
Strings are immutable in many languages (like Java, Python). You can’t delete by index directly.

---

### 25. **Which method converts string to uppercase in most languages?**

**A)** upper() ✅

**B)** up()

**C)** uppercase()

**D)** capital()

**Explanation:**
`upper()` is used in Python and similar libraries to convert strings to uppercase.

---

### 26. **Which of these is not used for string pattern matching?**

**A)** Rabin-Karp

**B)** KMP

**C)** Z-Algorithm

**D)** BFS ✅

**Explanation:**
BFS is a graph traversal algorithm, not used for string pattern matching.

---

### 27. **How many substrings can be formed from a string of length n?**

**A)** n

**B)** n²

**C)** n(n+1)/2 ✅

**D)** n³

**Explanation:**
The total number of substrings is the sum of lengths of all possible substrings.

---

### 28. **Which method compares two strings lexicographically?**

**A)** equals()

**B)** ==

**C)** compareTo() ✅

**D)** match()

**Explanation:**
`compareTo()` returns positive, negative, or zero based on lexicographic comparison.

---

### 29. **What will "abc".charAt(3) return?**

**A)** 'a'

**B)** 'c'

**C)** IndexOutOfBoundsException ✅

**D)** Null

**Explanation:**
Valid indices are 0 to 2. Index 3 is out of bounds → runtime error.

---

### 30. **Which technique helps in finding the longest palindromic substring?**

**A)** BFS

**B)** Stack

**C)** Expand Around Center ✅

**D)** Prefix Sum

**Explanation:**
This method checks all centers and expands to find palindromes efficiently in O(n²) time.

---


## ✅ **Topic: Matrix and 2D Arrays (31–45)**

---

### 31. **What is the time complexity of printing all elements of an N x M matrix?**

**A)** O(N + M)

**B)** O(N × M) ✅

**C)** O(N log M)

**D)** O(N²)

**Explanation:**
Each of the N rows contains M elements. You must access each of the N × M elements once → O(N×M).

---

### 32. **How do you transpose a square matrix in-place?**

**A)** Swap rows and columns ✅

**B)** Use a queue

**C)** Flip diagonally

**D)** Use 1D array

**Explanation:**
For in-place transpose, swap matrix\[i]\[j] with matrix\[j]\[i] for i < j.

---

### 33. **Which operation is used in rotating a matrix by 90 degrees clockwise?**

**A)** Reverse columns and transpose

**B)** Reverse rows and transpose ✅

**C)** Just transpose

**D)** No need for operation

**Explanation:**
For 90° clockwise rotation:
→ First transpose
→ Then reverse each row.

---

### 34. **Which of the following is correct for spiral traversal of a matrix?**

**A)** Top → Bottom → Right → Left

**B)** Left → Right → Bottom → Top

**C)** Top → Right → Bottom → Left ✅

**D)** Top → Left → Bottom → Right

**Explanation:**
In spiral traversal, we go layer by layer:
Top row → Right column → Bottom row → Left column.

---

### 35. **What is the time complexity of spiral traversal for N x N matrix?**

**A)** O(N)

**B)** O(N²) ✅

**C)** O(log N)

**D)** O(N log N)

**Explanation:**
You need to visit all N² elements in spiral order → O(N²).

---

### 36. **Which algorithm is efficient to search in a row-wise and column-wise sorted matrix?**

**A)** DFS

**B)** Binary Search on rows

**C)** Staircase Search ✅

**D)** BFS

**Explanation:**
Start from top-right and move left or down — O(N + M) time.

---

### 37. **What is the best data structure to represent a sparse matrix?**

**A)** 2D Array

**B)** Stack

**C)** Linked List or Dictionary ✅

**D)** Queue

**Explanation:**
Sparse matrices have mostly 0s. Use a map or list of triples (row, col, value) to save space.

---

### 38. **How many diagonals does an N x N matrix have (excluding the main diagonals)?**

**A)** 1

**B)** N

**C)** 2N - 1 ✅

**D)** N²

**Explanation:**
There are (N - 1) diagonals above and below the main diagonal → 2N - 1 including the main one.

---

### 39. **What is the space complexity of storing an N x M matrix?**

**A)** O(N + M)

**B)** O(N × M) ✅

**C)** O(1)

**D)** O(N²)

**Explanation:**
Every element must be stored individually, hence O(N×M).

---

### 40. **Which of the following does NOT apply to a symmetric matrix?**

**A)** A\[i]\[j] = A\[j]\[i]

**B)** Square matrix

**C)** Diagonal is zero ✅

**D)** A\[i]\[j] = A\[j]\[i]

**Explanation:**
Diagonal may or may not be zero. Symmetry only requires A\[i]\[j] = A\[j]\[i].

---

### 41. **In a matrix multiplication A (n×m) × B (m×p), result is of size?**

**A)** n×p ✅

**B)** m×n

**C)** m×m

**D)** n×n

**Explanation:**
The result of A × B has dimensions (rows of A) × (columns of B) → n×p.

---

### 42. **What is the time complexity of matrix multiplication (standard method)?**

**A)** O(n log n)

**B)** O(n²)

**C)** O(n³) ✅

**D)** O(2^n)

**Explanation:**
Standard method uses three nested loops → O(n³) for multiplying two n × n matrices.

---

### 43. **Which of the following algorithms is faster than the standard matrix multiplication?**

**A)** DFS

**B)** Strassen’s Algorithm ✅

**C)** Floyd-Warshall

**D)** Dijkstra

**Explanation:**
Strassen’s algorithm is a divide-and-conquer matrix multiplication with time complexity \~O(n^2.81).

---

### 44. **Which data structure is best suited for pathfinding in a matrix?**

**A)** Stack

**B)** DFS

**C)** Queue with BFS ✅

**D)** AVL Tree

**Explanation:**
Breadth-First Search (BFS) using a queue is optimal for finding the shortest path in an unweighted grid.

---

### 45. **Which of the following is true for diagonal sum in square matrix?**

**A)** One loop is enough ✅

**B)** Need to transpose

**C)** Use binary search

**D)** Need nested loop

**Explanation:**
Primary diagonal: `i == j`, Secondary diagonal: `i + j == n - 1`. One loop can sum both in a square matrix.

---


## ✅ **Topic: Stacks & Queues (46–60)**

---

### 46. **Which data structure follows LIFO order?**

**A)** Queue

**B)** Stack ✅

**C)** Linked List

**D)** Tree

**Explanation:**
LIFO = Last In, First Out — Stack follows this principle.

---

### 47. **What is the time complexity for push and pop in a stack?**

**A)** O(n)

**B)** O(log n)

**C)** O(1) ✅

**D)** O(n log n)

**Explanation:**
Both operations happen at one end (top), so it's constant time.

---

### 48. **Which of the following is used to convert infix to postfix?**

**A)** BFS

**B)** DFS

**C)** Stack ✅

**D)** Queue

**Explanation:**
Stack helps in handling operator precedence and brackets while converting expressions.

---

### 49. **What is the postfix expression of (A + B) \* (C - D)?**

**A)** AB+CD-\* ✅

**B)** AB+*CD-

**C)** A+B*C-D

**D)** A+B-C\*D

**Explanation:**
Postfix notation (Reverse Polish): operands first, then operator. Left to right → AB+CD-\*.

---

### 50. **Which data structure is used for recursion?**

**A)** Stack ✅

**B)** Queue

**C)** Heap

**D)** Tree

**Explanation:**
Function calls are managed by the call stack during recursion.

---

### 51. **What is the time complexity of checking balanced parentheses using stack?**

**A)** O(1)

**B)** O(log n)

**C)** O(n) ✅

**D)** O(n²)

**Explanation:**
You process each character once and use stack operations → O(n).

---

### 52. **Which of the following is NOT a stack application?**

**A)** Backtracking

**B)** Function calls

**C)** Expression evaluation

**D)** Level order traversal ✅

**Explanation:**
Level-order traversal uses a queue, not a stack.

---

### 53. **Which data structure follows FIFO order?**

**A)** Stack

**B)** Queue ✅

**C)** Array

**D)** Heap

**Explanation:**
FIFO = First In, First Out — Queue works in this manner.

---

### 54. **What is a circular queue?**

**A)** Queue with a loop

**B)** Queue using circular linked list

**C)** Queue where last points to first ✅

**D)** Stack in reverse

**Explanation:**
In circular queue, rear wraps around to front when reaching the end to utilize space efficiently.

---

### 55. **Which of the following is a linear data structure?**

**A)** Tree

**B)** Graph

**C)** Stack ✅

**D)** Trie

**Explanation:**
Stack is a linear structure — elements are arranged in a linear sequence.

---

### 56. **Which operation is not allowed in queue?**

**A)** Enqueue

**B)** Dequeue

**C)** Random access ✅

**D)** Front

**Explanation:**
You cannot access elements at a random index — only front and rear.

---

### 57. **In a dequeue, elements can be inserted/deleted from?**

**A)** Front only

**B)** Rear only

**C)** Both ends ✅

**D)** Middle only

**Explanation:**
Double-ended queue (deque) allows operations at both front and rear ends.

---

### 58. **Which of the following implements undo in text editors?**

**A)** Queue

**B)** Stack ✅

**C)** Heap

**D)** Linked List

**Explanation:**
Undo follows LIFO order, hence stack is ideal.

---

### 59. **Which is the correct order of postfix evaluation?**

**A)** Right to left

**B)** Left to right ✅

**C)** Tree traversal

**D)** Random

**Explanation:**
Postfix expressions are evaluated left to right using a stack.

---

### 60. **Which structure is best for implementing LRU Cache?**

**A)** Stack

**B)** Heap


**C)** HashMap + Doubly Linked List ✅

**D)** Queue

**Explanation:**
LRU (Least Recently Used) Cache requires O(1) access and deletion, achieved by combining a hashmap and DLL.

---

## ✅ **Topic: Linked Lists (61–75)**

---

### 61. **What is the time complexity to insert a node at the beginning of a singly linked list?**

**A)** O(1) ✅

**B)** O(n)

**C)** O(log n)

**D)** O(n²)

**Explanation:**
You just create a new node and point its next to head, then update head → constant time.

---

### 62. **Which data structure does not allow random access of elements?**

**A)** Array

**B)** Linked List ✅

**C)** Stack

**D)** Queue

**Explanation:**
Linked lists must be traversed node by node to access an element — no direct indexing.

---

### 63. **What is the time complexity to search for an element in a singly linked list?**

**A)** O(1)

**B)** O(log n)

**C)** O(n) ✅

**D)** O(n²)

**Explanation:**
You may have to traverse the entire list — linear time.

---

### 64. **Which of the following is used to detect a cycle in a linked list?**

**A)** BFS

**B)** DFS

**C)** Floyd’s Cycle Detection ✅

**D)** Kadane’s Algorithm

**Explanation:**
Also known as the “tortoise and hare” algorithm — uses slow and fast pointers to detect cycles.

---

### 65. **In a singly linked list, what does the last node point to?**

**A)** Head

**B)** NULL ✅

**C)** Middle

**D)** Itself

**Explanation:**
The last node’s next pointer is set to NULL to mark the end of the list.

---

### 66. **What is the key difference between singly and doubly linked lists?**

**A)** Doubly lists use arrays

**B)** Doubly lists have two pointers ✅

**C)** Singly lists are circular

**D)** Doubly lists are static

**Explanation:**
Doubly linked lists store both `next` and `prev` pointers per node.

---

### 67. **What is the space complexity of a doubly linked list with n nodes?**

**A)** O(n) ✅

**B)** O(n²)

**C)** O(log n)

**D)** O(1)

**Explanation:**
Each node stores two pointers, but the space still grows linearly with the number of nodes.

---

### 68. **Which operation is easiest in a doubly linked list compared to singly?**

**A)** Reversal

**B)** Deletion from the end ✅

**C)** Insertion at head

**D)** Traversal from head

**Explanation:**
In doubly linked list, you can easily move backwards, making end deletion easy in O(1).

---

### 69. **Which of the following is true for a circular linked list?**

**A)** It has a tail pointing to null

**B)** It has head pointing to tail

**C)** Last node points to head ✅

**D)** It’s not possible in C/C++

**Explanation:**
In circular linked lists, the last node’s next points back to the head.

---

### 70. **How many NULL pointers in a circular singly linked list with 5 nodes?**

**A)** 0 ✅

**B)** 1

**C)** 2

**D)** 5

**Explanation:**
In a circular list, no node’s next is NULL — all nodes link circularly.

---

### 71. **What is the best way to reverse a singly linked list?**

**A)** Recursion

**B)** Using stack

**C)** Iterative with three pointers ✅

**D)** Using array

**Explanation:**
Iterative method with three pointers (prev, current, next) is most efficient — O(n) time, O(1) space.

---

### 72. **What happens if you don’t update the head in a reversed list?**

**A)** It will point to middle

**B)** List will be lost ✅

**C)** Nothing changes

**D)** Memory error

**Explanation:**
Head still points to old node → reversed list becomes inaccessible.

---

### 73. **Which operation is expensive in a singly linked list?**

**A)** Insertion at head

**B)** Insertion at tail ✅

**C)** Searching

**D)** Traversing from head

**Explanation:**
Insertion at tail requires full traversal in singly list unless you maintain a tail pointer.

---

### 74. **Which of the following detects the intersection of two linked lists?**

**A)** Stack

**B)** Hashing or Two pointer ✅

**C)** Recursion

**D)** Floyd’s cycle

**Explanation:**
Two-pointer method (based on length difference) or hashing helps detect the node where lists intersect.

---

### 75. **What is the time complexity to merge two sorted linked lists?**

**A)** O(n + m) ✅

**B)** O(n log m)

**C)** O(n²)

**D)** O(log n + log m)

**Explanation:**
Traverse both lists once — O(n + m) time where n and m are lengths of the two lists.

---


## ✅ **Topic: Trees (76–90)**

---

### 76. **Which traversal prints the nodes in sorted order in a Binary Search Tree (BST)?**

**A)** Preorder

**B)** Inorder ✅

**C)** Postorder

**D)** Level-order

**Explanation:**
Inorder traversal (Left → Root → Right) of BST always results in sorted values.

---

### 77. **What is the maximum number of nodes in a binary tree of height `h`?**

**A)** 2ʰ

**B)** 2ʰ - 1 ✅

**C)** h²

**D)** h × 2

**Explanation:**
In a complete binary tree, maximum nodes = 2ʰ - 1.

---

### 78. **What is the height of a tree with only root node?**

**A)** -1

**B)** 0 ✅

**C)** 1

**D)** Undefined

**Explanation:**
Height is defined as the number of edges in the longest path from root to a leaf. Single node → height = 0.

---

### 79. **Which traversal is best suited for expression trees?**

**A)** Inorder

**B)** Preorder

**C)** Postorder ✅

**D)** Level-order

**Explanation:**
Postorder traversal evaluates expressions from the bottom up (operands → operators).

---

### 80. **Which of the following is not a binary tree type?**

**A)** Complete

**B)** Full

**C)** BST

**D)** B-Tree ✅

**Explanation:**
B-Tree is a general multi-way tree used in databases, not a binary tree.

---

### 81. **Which traversal uses a queue?**

**A)** Preorder

**B)** Inorder

**C)** Postorder

**D)** Level-order ✅

**Explanation:**
Level-order traversal uses a queue (BFS style) to visit nodes level-by-level.

---

### 82. **Time complexity of searching in a balanced BST (height = log n)?**

**A)** O(n)

**B)** O(log n) ✅

**C)** O(1)

**D)** O(n log n)

**Explanation:**
Balanced BSTs have height log n, so search requires log n comparisons in worst case.

---

### 83. **Which of the following is true for full binary tree?**

**A)** Every node has 0 or 2 children ✅

**B)** Nodes can have 3 children


**C)** All leaves are at same level

**D)** Height = number of nodes

**Explanation:**
A full binary tree is defined by nodes having either 0 or 2 children.

---

### 84. **Which data structure is used in tree traversals (recursive)?**

**A)** Queue

**B)** Stack ✅

**C)** Array

**D)** HashMap

**Explanation:**
Recursive calls use the function call stack, so it's a stack-based traversal.

---

### 85. **Which of the following trees is always balanced?**

**A)** Binary Tree

**B)** Binary Search Tree

**C)** AVL Tree ✅

**D)** Threaded Tree

**Explanation:**
AVL tree is a self-balancing BST where the height difference (balance factor) is at most 1.

---

### 86. **Which of the following gives postorder traversal of a binary tree?**

**A)** Root → Left → Right

**B)** Left → Right → Root ✅

**C)** Right → Root → Left

**D)** Right → Left → Root

**Explanation:**
Postorder traversal: Left → Right → Root.

---

### 87. **Which of the following helps in finding diameter of a binary tree?**

**A)** Height of left + height of right ✅

**B)** Maximum width

**C)** Sum of depths

**D)** Number of leaves

**Explanation:**
Diameter is the longest path between any two nodes — calculated as `leftHeight + rightHeight + 1`.

---

### 88. **Which of these is not a tree traversal method?**

**A)** Inorder

**B)** Preorder

**C)** Uporder ✅

**D)** Postorder

**Explanation:**
"Uporder" is not a valid traversal. The correct ones are Inorder, Preorder, Postorder, Level-order.

---

### 89. **Minimum number of nodes in an AVL tree of height `h`?**

**A)** h

**B)** 2ʰ - 1

**C)** Fibonacci(h+2) - 1 ✅

**D)** log h

**Explanation:**
The minimum nodes in an AVL tree follow a Fibonacci-like recurrence: N(h) = N(h-1) + N(h-2) + 1.

---

### 90. **What is the balance factor of a node in an AVL tree?**

**A)** height(left) + height(right)

**B)** height(left) - height(right) ✅

**C)** right - left

**D)** absolute(height)

**Explanation:**
Balance factor = height of left subtree - height of right subtree. Must be in {-1, 0, 1}.

---

## ✅ **Topic: Graphs, Heaps, and Tries (91–100)**

---

### 91. **Which graph traversal uses a queue?**

**A)** DFS

**B)** BFS ✅

**C)** Topological Sort

**D)** Dijkstra

**Explanation:**
BFS (Breadth-First Search) uses a queue to explore neighbors level by level.

---

### 92. **Which of the following is used in Depth First Search (DFS)?**

**A)** Queue

**B)** Stack ✅

**C)** Priority Queue

**D)** Heap

**Explanation:**
DFS explores as deep as possible using recursion or an explicit stack.

---

### 93. **Which algorithm finds the shortest path in a weighted graph (no negative weights)?**

**A)** BFS

**B)** DFS

**C)** Dijkstra ✅

**D)** Kruskal

**Explanation:**
Dijkstra’s algorithm finds the shortest paths using a priority queue — only works with non-negative weights.

---

### 94. **Which data structure is used in Dijkstra’s algorithm for priority management?**

**A)** Stack

**B)** Heap (Min-Heap) ✅

**C)** Queue

**D)** Tree

**Explanation:**
Dijkstra uses a min-heap (priority queue) to efficiently get the next minimum distance node.

---

### 95. **Which algorithm is used to find a Minimum Spanning Tree (MST)?**

**A)** Dijkstra

**B)** Kruskal ✅

**C)** Floyd-Warshall

**D)** Bellman-Ford

**Explanation:**
Kruskal’s and Prim’s algorithms are standard methods to find MSTs in a connected graph.

---

### 96. **Which algorithm works with negative weights but no negative cycles?**

**A)** Dijkstra

**B)** Bellman-Ford ✅

**C)** DFS

**D)** Prim

**Explanation:**
Bellman-Ford handles negative weights and detects negative cycles in O(V×E) time.

---

### 97. **What is the time complexity of BFS in a graph with V vertices and E edges?**

**A)** O(V)

**B)** O(V + E) ✅

**C)** O(E log V)

**D)** O(V²)

**Explanation:**
Each vertex and edge is visited once in BFS → O(V + E).

---

### 98. **In a min-heap, which element is always at the root?**

**A)** Maximum element

**B)** Random element

**C)** Minimum element ✅

**D)** Median element

**Explanation:**
In a min-heap, the smallest value is always at the root by definition.

---

### 99. **Which operation has O(log n) time in a binary heap?**

**A)** Insert ✅

**B)** Search

**C)** Access min

**D)** Peek

**Explanation:**
Insertion may require bubbling up → O(log n). Accessing min is O(1), search is O(n).

---

### 100. **What is a Trie used for?**

**A)** Sorting integers

**B)** Storing IP addresses ✅

**C)** Finding MST

**D)** Dynamic programming

**Explanation:**
Tries are prefix trees, ideal for word storage, autocomplete, IP routing, etc.

---


