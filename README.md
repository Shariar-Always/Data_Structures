# 📚 Data Structures Lab (CSE124)

![Language](https://img.shields.io/badge/Language-C%20%7C%20C%2B%2B-blue.svg)
![Course](https://img.shields.io/badge/Course-CSE124%20Data%20Structures%20Lab-orange.svg)
![Institution](https://img.shields.io/badge/University-Daffodil%20International%20University-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

A structured academic repository containing foundational implementations of fundamental **Data Structures** written in **C and C++**, developed as part of the **CSE124: Data Structures Lab** curriculum at **Daffodil International University (DIU)**.

---

## 📌 Table of Contents
- [📖 Course Overview](#-course-overview)
- [🛠️ Technologies & Tools](#️-technologies--tools)
- [📂 Lab Modules & Curriculum](#-lab-modules--curriculum)
  - [Lab 2: Singly Linked List](#lab-2-singly-linked-list)
  - [Lab 3: Doubly Linked List & Deletion](#lab-3-doubly-linked-list--deletion)
  - [Lab 4: Stack Implementation](#lab-4-stack-implementation)
  - [Lab 5: Queue Implementation](#lab-5-queue-implementation)
  - [Lab 6: Binary Trees](#lab-6-binary-trees)
- [🚀 How to Compile & Run](#-how-to-compile--run)
- [👨‍💻 Author & Academic Information](#-author--academic-information)
- [📜 License](#-license)

---

## 📖 Course Overview
This repository covers practical, from-scratch implementations of linear and non-linear data structures, focusing on dynamic memory allocation (`malloc`, `free`), pointers, node linking, time/space complexity, and algorithmic operations.

---

## 🛠️ Technologies & Tools
- **Languages:** C, C++
- **Compiler:** GCC (MinGW)
- **IDE:** Visual Studio Code / Code::Blocks
- **Debugging & Analysis:** GDB, Pointer memory tracing

---

## 📂 Lab Modules & Curriculum

```bash
Data_Structures/
│
├── Lab2/                            # Singly Linked List Operations
│   ├── LinkedListCreation.c         # Static and user-input node creation
│   ├── DynamicLinkedList.c          # Dynamic memory allocation for nodes
│   ├── LinkedListInsertion.c        # Insertion (at beginning, end, and specific position)
│   └── LinkedListSearching.c        # Linear search in linked list
│
├── Lab3/                            # Advanced Linked List Operations
│   ├── DoublyLinkedList.c           # Bidirectional traversal with prev/next pointers
│   └── LinkedListDeletion.c         # Deletion (from head, tail, and target value)
│
├── Lab4/                            # Stack (LIFO)
│   ├── StackUsingArray.c            # Fixed-size stack implementation with overflow/underflow checks
│   └── StackUsingLinkedList.c       # Dynamic stack implementation
│
├── Lab5/                            # Queue (FIFO)
│   ├── QueueUsingArray.c            # Linear queue with front & rear pointers
│   └── QueueUsingLinkedList.c       # Dynamic queue implementation
│
├── Lab6/                            # Non-Linear Data Structures (Trees)
│   └── Tree.c                       # Binary tree node structure, creation, and traversals
│
├── Stack-Push-Pop.cpp               # C++ implementation of interactive Stack Push/Pop
└── README.md                        # Documentation
```

---

### Key Data Structures Covered:
1. **Singly & Doubly Linked Lists:** Dynamic node chaining, pointer manipulation, and traversal.
2. **Stack (LIFO - Last In First Out):** Push, Pop, Peek/Top operations using both arrays and dynamic nodes.
3. **Queue (FIFO - First In First Out):** Enqueue and Dequeue operations using arrays and linked lists.
4. **Binary Trees:** Hierarchical data representation, node structures, and tree traversal algorithms.

---

## 🚀 How to Compile & Run

To compile any C file, open terminal in the directory and use GCC:

```bash
# Compile a C program
gcc Lab2/LinkedListCreation.c -o app

# Run the compiled executable
./app
```

For C++ programs:
```bash
g++ Stack-Push-Pop.cpp -o stack_app
./stack_app
```

---

## 👨‍💻 Author & Academic Information

* **Student Name:** Shahriar Ahammed
* **GitHub:** [@Shariar-Always](https://github.com/Shariar-Always)
* **Portfolio:** [shariarahamed.com](https://www.shariarahamed.com)
* **Student ID:** 0242310005101019
* **Department:** Computer Science and Engineering
* **University:** Daffodil International University (DIU)
* **Course:** CSE124 – Data Structures Lab

---

## 📜 License
This repository is maintained for educational reference and academic study purposes.
