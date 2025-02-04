Binary Search Tree (BST) Implementation in Java

Overview:
This project implements a Binary Search Tree (BST) in Java with functionalities such as:
Insertion of nodes
Deletion of nodes
Searching for a node
Inorder, Preorder, and Postorder traversals
Features:
  Insertion (insert): Adds a new node to the BST.
  Deletion (deleteKey): Removes a node from the BST while maintaining its properties.
  Search (search): Checks if a given key exists in the BST.
  Traversals:
    Inorder (inorder): Left -> Root -> Right
    Preorder (preorder): Root -> Left -> Right
    Postorder (postorder): Left -> Right -> Root
    Implementation Details
  The BST is implemented using a Node class and a BST class.
  Recursive methods are used for insertion, deletion, and searching.
  A utility function minValue is used to find the smallest node in a subtree for deletion.
  
  Code Structure
    ├── BST.java  # Main Java file containing BST implementation
    ├── README.md # Documentation file

  Sample Output
  Inorder traversal:
    20 30 40 50 60 70 80 
  Preorder traversal:
    50 30 20 40 70 60 80 
  Postorder traversal:
    20 40 30 60 80 70 50
  Delete 20:
  Inorder traversal after deletion:
    30 40 50 60 70 80
  Search 40:
    true
  Search 100:
    false

  Contributions
    Feel free to contribute by creating issues or submitting pull requests!
