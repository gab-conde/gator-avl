# gator-avl

## Problem Statement

Binary Search Trees (BST) can often be an efficient and useful way to store and retrieve sorted data. However, the efficiency of these data trees relies heavily on how balanced a BST is. For example, searching through the BST on the left is much more efficient than searching through the BST on the right, despite both figures showing valid BST with the exact same elements.  
![image](https://github.com/gab-conde/gator-avl/assets/108101811/2219e6e6-e137-4de5-8819-ab74fcb877cb)  

To avoid inefficient binary search trees, we use balanced Binary Search Trees.  A balanced BST has a balance factor of less than ±threshold, where the balance factor is the difference in heights of the left and right subtrees at any given tree node. One such balanced tree is an AVL tree that maintains a threshold of 1. As soon as a node in an AVL tree has a balance factor of +2/-2, “tree rotations” are performed to maintain balance in the tree.  

In this project, you will be designing a custom AVL tree to organize UF student accounts based on GatorIDs. You will build methods for insertion, deletion, search, and traversals for an AVL tree data structure. These methods would be called based on certain commands that are invoked in the main method. You are responsible for 
- Designing the interface/modules/functions of the standard AVL Tree and the operations required to execute the respective commands.
- Parsing the input and ensuring data and command validation,
- Building the main function to parse the inputs and calling the respective functions to match the output.
- Testing your code within the constraints.

## Functionality

Your program must support the following commands: 
![image](https://github.com/gab-conde/gator-avl/assets/108101811/ac898908-5b9a-45c4-ae35-8cd591812b71)

## AVL Tree Data Structure

In order to receive full credit for this project, you must attempt to create an AVL Tree data structure/object class that is used in your main program. Additionally, this AVL tree should:
- Also meet the requirements for a Binary Search Tree (BST)
- Be sorted by numerical GatorID, not lexical Name
- Be sorted from least to greatest (nodes of lesser value are in the left subtree, nodes of greater value are in the right subtree)
- Make appropriate use of public and private methods
