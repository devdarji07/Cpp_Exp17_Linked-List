# Cpp_Exp17_Linked-List
# 📘 Experiment: Linked Lists in C++

---

## 🎯 AIM
To study and implement the concept of linked lists in C++ by performing the following operations:
1. Creating multiple nodes and linking them together.  
2. Initializing and printing the contents of a single node.  
3. Inserting nodes at the head of a linked list and displaying the result.  

---

## 📌 OBJECTIVES
- To understand the structure and functioning of a Node in a linked list.  
- To study the use of dynamic memory allocation in data structures.  
- To compare arrays and linked lists in terms of memory management and efficiency.  
- To implement basic operations on a linked list such as creation, traversal, and insertion.  

---

## 📖 THEORY

### 🔹 Introduction to Linked Lists
A linked list is a linear data structure consisting of nodes. Each node contains:
- **Data field** → stores the actual data value.  
- **Pointer field** → stores the address of the next node.  

The first node is called the **head**, and the last node points to **NULL**.  

**Key Differences from Arrays:**
- Uses **dynamic memory allocation**.  
- Does not require **contiguous memory**.  
- Allows efficient **insertion and deletion**.  

### 🔹 Types of Linked Lists
- **Singly Linked List** → Each node points to the next node.  
- **Doubly Linked List** → Each node points to both next and previous nodes.  
- **Circular Linked List** → The last node links back to the first node.  

👉 In this experiment, we demonstrate a **singly linked list**.

---

## ⚡ KEY CONCEPTS APPLIED
- **Classes and Objects** – Node representation.  
- **Constructors** – For initialization.  
- **Pointers** – For linking nodes.  
- **Dynamic Memory Allocation (`new`)** – Runtime memory creation.  
- **Traversal** – Iterating till NULL.  
- **Insertion at Head** – Adding nodes dynamically at the start.  

---

## 🆚 ARRAYS vs LINKED LISTS

| Feature            | Arrays (Static)            | Linked Lists (Dynamic)        |
|--------------------|----------------------------|--------------------------------|
| Memory Allocation  | Fixed & contiguous         | Dynamic & non-contiguous       |
| Insertion/Deletion | Time-consuming (shifting)  | Efficient (pointer adjustment) |
| Access Time        | O(1) – direct indexing     | O(n) – sequential traversal    |
| Memory Utilization | May waste unused memory    | Grows/shrinks as needed        |

---

## 📊 COMPARISON OF PROGRAMS

| Aspect         | Program 1                  | Program 2                     | Program 3                      |
|----------------|----------------------------|--------------------------------|--------------------------------|
| Purpose        | Manual linking             | Initialization of one node     | Insertion operation            |
| Nodes Created  | 3                          | 1                              | Multiple (dynamic)             |
| Traversal      | Yes                        | No                             | Yes                            |
| Reusability    | Low                        | Low                            | High (functions used)          |
| Practical Use  | Basic concept              | Syntax check                   | Realistic linked list handling |

---

## 📝 PROGRAM DESCRIPTIONS

### 🔹 Program 1: Creating & Linking Three Nodes
- Creates three nodes manually.  
- Links them sequentially.  
- Traverses and prints all values.  

### 🔹 Program 2: Single Node Initialization
- Creates one node dynamically.  
- Displays its data and pointer (NULL).  

### 🔹 Program 3: Insertion at Head
- Starts with an empty list.  
- Inserts new nodes at the **head** one by one.  
- Displays the list after each insertion.  

---

## ⚙️ ALGORITHMS

### ✅ Program 1 (Creating & Printing 3 Nodes)
1. Define node structure (data + pointer).  
2. Dynamically create 3 nodes.  
3. Link them sequentially.  
4. Traverse from head until NULL, printing values.  

### ✅ Program 2 (Single Node Initialization)
1. Define node structure with constructor.  
2. Create a node dynamically with a value.  
3. Print node data and pointer.  

### ✅ Program 3 (Insertion at Head)
1. Define node structure with constructor.  
2. Write `insert_head()` function:  
   - Create new node.  
   - Point it to current head.  
   - Update head pointer.  
3. Write `display()` function to print the list.  

---

## 🧩 CONCEPTS USED
- **OOP Concepts**: Classes, objects, constructors.  
- **Dynamic Memory**: Allocated at runtime with `new`.  
- **Pointers & Linking**: Establishing connections between nodes.  
- **NULL Termination**: Marks the end of a list.  
- **Traversal & Insertion**: Core linked list operations.  

---

## ✅ CONCLUSION
- **Program 1** → Introduced creation & manual linking of nodes.  
- **Program 2** → Showed initialization & printing of a single node.  
- **Program 3** → Demonstrated insertion at head with traversal.  

Linked lists are **dynamic, flexible** structures compared to arrays, and form the base for advanced data structures like **stacks, queues, and graphs**.  

---
