# 🔹 Trees & Graphs – DSA in C

This folder contains **fundamental Binary Tree and Graph algorithms** implemented  
using **C programming language**. These problems are crucial for understanding  
**hierarchical data structures**, **graph traversal**, and are widely asked in  
**DSA exams**, **interviews**, and **Advanced Programming Practice (APP)**.

---

## 🌳 Binary Tree Problems

### 1️⃣ Inorder Traversal of a Binary Tree
**Problem:**  
Perform an inorder traversal of a binary tree.

**Traversal Order:**  
Left → Root → Right

**Approach:**  
- Recursively traverse left subtree  
- Visit root node  
- Recursively traverse right subtree  

**Time Complexity:** O(n)  
**Space Complexity:** O(h)

---

### 2️⃣ Preorder Traversal of a Binary Tree
**Problem:**  
Perform a preorder traversal of a binary tree.

**Traversal Order:**  
Root → Left → Right

**Approach:**  
- Visit root node first  
- Traverse left subtree  
- Traverse right subtree  

**Time Complexity:** O(n)  
**Space Complexity:** O(h)

---

### 3️⃣ Postorder Traversal of a Binary Tree
**Problem:**  
Perform a postorder traversal of a binary tree.

**Traversal Order:**  
Left → Right → Root

**Approach:**  
- Traverse left subtree  
- Traverse right subtree  
- Visit root node  

**Time Complexity:** O(n)  
**Space Complexity:** O(h)

---

### 4️⃣ Height of a Binary Tree
**Problem:**  
Calculate the height (maximum depth) of a binary tree.

**Approach:**  
- Height of empty tree = 0  
- Height = `1 + max(left height, right height)`

**Time Complexity:** O(n)  
**Space Complexity:** O(h)

---

## 🌐 Graph Problems

### 5️⃣ Breadth First Search (BFS)
**Problem:**  
Traverse a graph using the Breadth First Search (BFS) algorithm.

**Approach:**  
- Use a **queue**  
- Visit vertices level by level  
- Use a visited array to avoid revisits  

**Time Complexity:** O(V + E)  
**Space Complexity:** O(V)

---

### 6️⃣ Depth First Search (DFS)
**Problem:**  
Traverse a graph using the Depth First Search (DFS) algorithm.

**Approach:**  
- Use **recursion**  
- Explore as deep as possible before backtracking  
- Maintain a visited array  

**Time Complexity:** O(V + E)  
**Space Complexity:** O(V)

---

## 🛠️ Language Used
- **C Programming Language**

---

## 📁 Recommended Folder Structure
