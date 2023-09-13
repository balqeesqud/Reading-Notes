# Binary Trees Quick Reference Guide

Binary trees are fundamental data structures in computer science. This concise reference guide summarizes key binary 
tree concepts and operations.

## Essential Terminology

- **Node:** The fundamental building block of a binary tree, housing data and references to its left and right children.
- **Root:** The top node of a binary tree, serving as the starting point.
- **Leaf:** A node devoid of children (both left and right references are null).
- **Parent:** A node with one or more children.
- **Child:** Nodes directly linked to a parent node.

## Types of Binary Trees

- **Binary Search Tree (BST):** A binary tree where values in the left subtree are less than or equal to the root, 
    and values in the right subtree are greater than the root.
- **Balanced Binary Tree:** A binary tree ensuring minimal difference in depth between left and right subtrees for 
    efficient operations.
- **Complete Binary Tree:** A tree with fully filled levels, except for the possibly incomplete last level filled 
    from left to right.
- **Full Binary Tree:** A tree in which each node has 0 or 2 children (no nodes with just one child).
- **Perfect Binary Tree:** A tree in which all internal nodes have precisely two children, and all leaf nodes share
    the same level.

## Binary Tree Traversal Techniques

- **Inorder Traversal:** Left, Root, Right (yields ascending order in a BST).
- **Preorder Traversal:** Root, Left, Right (useful for copying the tree).
- **Postorder Traversal:** Left, Right, Root (useful for tree deletion).
- **Level-order Traversal:** Sequentially visit nodes from left to right at each level using a queue 
    (Breadth-First Search).

## Common Operations

- **Insertion:** Add a new node by comparing values and navigating left or right until an empty spot is found.
- **Deletion:** Remove a node while preserving the binary tree's structure, accounting for various scenarios
    (no children, one child, two children).
- **Search:** Traverse the tree via comparisons to locate a specific node.
- **Balancing:** Reorganize the tree to maintain balance, as seen in AVL trees and Red-Black trees.
- **Height/Depth:** Determine the maximum depth (longest root-to-leaf path) of the tree.

## Practical Applications

- Binary trees are essential components of numerous algorithms and data structures, including binary searches, 
  heaps, expression trees, and more.
- They excel in efficient search, insertion, and deletion when properly balanced.

## Common Pitfalls(Mistakes)

- Neglecting the preservation of the binary search property during insertion and deletion in a BST.
- Failing to balance a binary tree, resulting in suboptimal performance during operations.

Bear in mind that a solid grasp of binary trees is vital for tackling a wide range of computer science and 
programming challenges with efficiency. This reference guide is a handy resource when working with binary trees.
