Java AVL Tree
# Overview
This project implements an AVL Tree in Java. An AVL Tree is a self-balancing Binary Search Tree (BST) that automatically maintains its height balance after every insertion or deletion, ensuring efficient search, insertion, and deletion operations.

This implementation includes AVL rotations and preorder traversal, making it suitable for learning Data Structures and Algorithms.

# Features
* AVL Tree implementation in Java

* Self-balancing Binary Search Tree

* Insert nodes

* Preorder traversal

* Automatic balancing after insertion

* Supports all four AVL rotations:

-> Left-Left (LL)
-> Right-Right (RR)
-> Left-Right (LR)
-> Right-Left (RL)
# Technologies Used
* Java
* Object-Oriented Programming (OOP)
# Project Structure
java-avl-tree/

│── AVLTree.java

└── README.md

# How to Run
1. Clone the repository

git clone https://github.com/your-username/java-avl-tree.git

2. Navigate to the project folder

cd java-avl-tree

3. Compile the program
   
javac AVLTree.java

4. Run the program

java AVLTree

# Sample Output

Preorder Traversal of AVL Tree:
30 20 10 25 40 50
# Time Complexity

Operation   	Complexity

Search	     O(log n)
Insert	     O(log n)
Delete      	O(log n)
Traversal   	O(n)

# AVL Tree Rotations

The program automatically performs the following rotations to maintain balance:

-> Left-Left (LL)
-> Right-Right (RR)
-> Left-Right (LR)
->Right-Left (RL)

These rotations ensure that the height difference between the left and right subtrees remains within one.

# Learning Outcomes

By studying this project, you will learn:

* Binary Search Trees (BST)
* AVL Trees
* Tree Rotations
* Recursion
* Object-Oriented Programming in Java
* Time Complexity Analysis
  
# Future Improvements
* Add deletion operation
  
* Add inorder and postorder traversals
  
* Implement level-order traversal
  
* Visualize the tree structure
  
* Add unit tests
  
author
Gummadisani Archana
