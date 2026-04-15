# 🚀 Custom Data Structures in C#

This project contains custom implementations of classic data structures using **C#**, built from scratch with a focus on understanding internal behavior, performance, and clean code practices.

---

## 📚 Implemented Structures

* 🔗 **Doubly Linked List** (`DoublyLinkedList<T>`)
* 📥 **Queue (FIFO)** (`NewQueue<T>`)

---

## 🧠 Key Concepts

* Generics (`<T>`)
* Data Structures (Linked Lists, Queue)
* FIFO (First In, First Out)
* Encapsulation
* Code Reusability
* Algorithm Complexity (Big-O)
* Clean Code principles

---

## ⚙️ Queue Implementation

The queue is implemented using a **doubly linked list**:

* `Enqueue` → adds an element to the end (Tail)
* `Dequeue` → removes the element from the beginning (Head)
* `Peek` → returns the first element without removing it

---

## 💻 Usage Example

```csharp
var queue = new NewQueue<int>();

queue.Enqueue(10);
queue.Enqueue(20);
queue.Enqueue(30);

Console.WriteLine(queue.Peek); // 10

queue.Dequeue();

Console.WriteLine(queue.Peek); // 20
```

---

## 📊 Time Complexity

| Operation | Complexity |
| --------- | ---------- |
| Enqueue   | O(1)       |
| Dequeue   | O(1)       |
| Peek      | O(1)       |

---

## 🧪 Unit Tests

This project includes unit tests built with **NUnit**, covering:

* Core behaviors (enqueue, dequeue, peek)
* Edge cases (empty queue, full queue)
* FIFO order validation
* Generic type support

---

## 📊 Test Coverage

Test coverage is measured using **coverlet** and **reportgenerator**.

> ✔ High coverage focused on behavior and edge cases

---

## 🎯 Purpose

This project was created to:

* Deeply understand how data structures work internally
* Practice implementing algorithms from scratch
* Improve problem-solving and coding skills in C#
* Build a strong technical foundation for software development

---

## 📁 Project Structure

```
DataStructures/
│
├── src/
│   ├── DoublyLinkedList.cs
│   └── NewQueue.cs
│
├── tests/
│   └── NewQueueTests.cs
│
├── README.md
└── DataStructures.sln
```

---

## 👨‍💻 Author

**Thiago Santiago Rodrigues**
Aspiring Full Stack Developer 🚀

---

## ⭐ If you like this project

Give it a star and feel free to explore or contribute!

