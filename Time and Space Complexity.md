## 1. *Array*

| Operation         | Time Complexity | Space Complexity  |
| ----------------- | --------------- | ----------------- |
| Access (by index) | O(1)            | O(n) (array size) |
| Search (linear)   | O(n)            | O(1)              |
| Insert (end)      | O(1) amortized  | O(n)              |
| Insert (middle)   | O(n)            | O(n)              |
| Delete (middle)   | O(n)            | O(1)              |

---

## 2. *Linked List*

| Operation         | Time Complexity | Space Complexity |
| ----------------- | --------------- | ---------------- |
| Access (by index) | O(n)            | O(n)             |
| Search            | O(n)            | O(1)             |
| Insert (head)     | O(1)            | O(n)             |
| Insert (middle)   | O(n)            | O(1)             |
| Delete            | O(n)            | O(1)             |

---
## 3. *Stack / Queue*

| Operation       | Time Complexity | Space Complexity |
| --------------- | --------------- | ---------------- |
| Push/Enqueue    | O(1)            | O(n)             |
| Pop/Dequeue     | O(1)            | O(n)             |
| Peek/Front/Rear | O(1)            | O(n)             |

---

## 4. *Hash Table (Hash Map)*

| Operation | Time Complexity (avg) | Time Complexity (worst) | Space Complexity |
| --------- | --------------------- | ----------------------- | ---------------- |
| Search    | O(1)                  | O(n)                    | O(n)             |
| Insert    | O(1)                  | O(n)                    | O(n)             |
| Delete    | O(1)                  | O(n)                    | O(n)             |

---

## 5. *Binary Search Tree (BST)*

| Operation | Time Complexity (avg) | Time Complexity (worst) | Space Complexity |
| --------- | --------------------- | ----------------------- | ---------------- |
| Search    | O(log n)              | O(n)                    | O(n)             |
| Insert    | O(log n)              | O(n)                    | O(n)             |
| Delete    | O(log n)              | O(n)                    | O(n)             |

---
## 6. *Balanced Trees (AVL, Red-Black Tree)*

| Operation | Time Complexity | Space Complexity |
| --------- | --------------- | ---------------- |
| Search    | O(log n)        | O(n)             |
| Insert    | O(log n)        | O(n)             |
| Delete    | O(log n)        | O(n)             |

---

## 7. *Heap (Binary Heap)*

| Operation       | Time Complexity | Space Complexity |
| --------------- | --------------- | ---------------- |
| Insert          | O(log n)        | O(n)             |
| Extract Min/Max | O(log n)        | O(n)             |
| Peek Min/Max    | O(1)            | O(n)             |

---

## 8. *Graph (Adjacency List)*

| Operation            | Time Complexity | Space Complexity |
| -------------------- | --------------- | ---------------- |
| Add Vertex           | O(1)            | O(V + E)         |
| Add Edge             | O(1)            | O(V + E)         |
| Search (DFS or BFS)  | O(V + E)        | O(V)             |
| Check Edge Existence | O(V)            | O(V + E)         |

---

## 9. *Sorting Algorithms*

| Algorithm      | Time Complexity (Best) | Time Complexity (Avg) | Time Complexity (Worst) | Space Complexity |
| -------------- | ---------------------- | --------------------- | ----------------------- | ---------------- |
| Bubble Sort    | O(n)                   | O(n²)                 | O(n²)                   | O(1)             |
| Insertion Sort | O(n)                   | O(n²)                 | O(n²)                   | O(1)             |
| Selection Sort | O(n²)                  | O(n²)                 | O(n²)                   | O(1)             |
| Merge Sort     | O(n log n)             | O(n log n)            | O(n log n)              | O(n)             |
| Quick Sort     | O(n log n)             | O(n log n)            | O(n²)                   | O(log n)         |
| Heap Sort      | O(n log n)             | O(n log n)            | O(n log n)              | O(1)             |

---
