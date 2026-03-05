## 1️⃣ Singly Linked List

![Image](https://miro.medium.com/1%2AiiEWrP2IznA6HbmuIdK0lQ.png)

![Image](https://deen3evddmddt.cloudfront.net/uploads/content-images/singly-linked-list-operations-in-data-structure.webp)

![Image](https://www.w3resource.com/w3r_images/c-linked_list-exercise-4-image.png)


![Image](https://static.afteracademy.com/images/types-of-linked-list-and-operation-on-linked-list-insert-begin-c5d6d8aebb19c584.png)

### 🔹 Representation

A **Singly Linked List** is represented by a pointer to the first node (`head`).
Each node contains:

* **Data** → stores actual information
* **Next** → pointer to the next node

```cpp
// Structure to represent the singly linked list
struct Node {
    int data;          // Data field
    struct Node* next; // Pointer to next node
};
```

---

### 🔹 Basic Operations

| Operation | Type           | Time Complexity | Space Complexity |
| --------- | -------------- | --------------- | ---------------- |
| Insertion | At Beginning   | O(1)            | O(1)             |
| Insertion | At End         | O(N)            | O(1)             |
| Insertion | At Position    | O(N)            | O(1)             |
| Deletion  | From Beginning | O(1)            | O(1)             |
| Deletion  | From End       | O(N)            | O(1)             |
| Deletion  | Specific Node  | O(N)            | O(1)             |
| Traversal | Start to End   | O(N)            | O(1)             |

---

## 2️⃣ Doubly Linked List

![Image](https://miro.medium.com/1%2AlCPgbrm9f7MQ75hvGV5p8Q.gif)

![Image](https://files.codingninjas.in/article_images/features-of-doubly-linked-list-0-1694106736.webp)

![Image](https://files.prepinsta.com/2023/02/Insertion-in-Doubly-Linked-List-in-C-1-1024x512.webp)

![Image](https://www.alphacodingskills.com/imgfiles/doubly-linked-list-add-node-at-start.PNG)

### 🔹 Representation

A **Doubly Linked List** has two pointers in each node:

* **Data** → stores actual information
* **Next** → pointer to next node
* **Prev** → pointer to previous node

The first node’s `prev = NULL`
The last node’s `next = NULL`

```cpp
// Structure to represent the doubly linked list
struct Node {
    int data;           // Data field
    struct Node* next;  // Pointer to next node
    struct Node* prev;  // Pointer to previous node
};
```

---

### 🔹 Basic Operations

| Operation | Type             | Time Complexity | Space Complexity |
| --------- | ---------------- | --------------- | ---------------- |
| Insertion | At Beginning     | O(1)            | O(1)             |
| Insertion | At End           | O(N)            | O(1)             |
| Insertion | At Position      | O(N)            | O(1)             |
| Deletion  | From Beginning   | O(1)            | O(1)             |
| Deletion  | From End         | O(N)            | O(1)             |
| Deletion  | Specific Node    | O(N)            | O(1)             |
| Traversal | Forward/Backward | O(N)            | O(1)             |

---

## 3️⃣ Circular Linked List

![Image](https://deen3evddmddt.cloudfront.net/uploads/content-images/what-is-circular-linked-list.webp)

![Image](https://favtutor.com/resources/images/uploads/mceu_90900768441611919048461.jpg)

![Image](https://files.codingninjas.in/article_images/circular-linked-list-traversal-0-1641491072.webp)

![Image](https://deen3evddmddt.cloudfront.net/uploads/content-images/singly-circular-linked-list.webp)

### 🔹 Representation

A **Circular Linked List** is similar to a singly linked list, except:

* The last node’s `next` pointer points back to the **first node**
* No node contains `NULL` in the `next` pointer (in a non-empty list)

```cpp
// Structure to represent the circular linked list
struct Node {
    int data;          // Data field
    struct Node* next; // Pointer to next node
};
```

---

### 🔹 Basic Operations

| Operation | Type               | Time Complexity | Space Complexity |
| --------- | ------------------ | --------------- | ---------------- |
| Insertion | At Beginning       | O(N)            |                  |
| Insertion | At End             | O(N)            |                  |
| Insertion | At Position        | O(N)            |                  |
| Deletion  | From Beginning     | O(N)            |                  |
| Deletion  | From End           | O(N)            |                  |
| Deletion  | Specific Node      | O(N)            |                  |
| Traversal | Circular Traversal | O(N)            |                  |

---

# 📌 Applications of Linked Lists

* ✔ Dynamic memory allocation
* ✔ Undo/Redo operations in text editors
* ✔ Adjacency list representation in graphs
* ✔ Implementing Stack and Queue
* ✔ Media players (circular playlist rotation)

---

# ✅ Advantages of Linked List

* Efficient insertion and deletion (no shifting like arrays)
* Dynamic size (can grow/shrink at runtime)
* Better memory utilization (no pre-allocation required)
* Useful for frequently changing datasets
* Uses non-contiguous memory blocks

---

# ❌ Disadvantages of Linked List

* No direct/random access (must traverse)
* Extra memory required for pointers
* More complex to implement
* Pointer-related issues (memory leaks, segmentation faults)

---

If you'd like, I can also provide:

* 🔹 Complete C++ implementation
* 🔹 Comparison between Array vs Linked List
* 🔹 Interview questions on Linked Lists
* 🔹 Practice problems

Just tell me 😊
