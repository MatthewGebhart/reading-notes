# Class 15 - Trees

## Reading

[Source Credit](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

Terminology
- Node - A Tree node is a component which may contain its own values, and references to other nodes
- Root - The root is the node at the beginning of the tree
- K - A number that specifies the maximum number of children any node may have in a k-ary tree. In a binary tree, k = 2.
- Left - A reference to one child node, in a binary tree
- Right - A reference to the other child node, in a binary tree
- Edge - The edge in a tree is the link between a parent and child node
- Leaf - A leaf is a node that does not have any children
- Height - The height of a tree is the number of edges from the root to the furthest leaf
- most common wat to traverse through a tree is to use **recursion**
- depth first vs breadth first
- depth first will go all the way down the tree to the leaf level before going back up, uses recursion to traverse down building a call stack
- breadth first will go through each level of the tree node by node and uses a queue to traverse
- K-ary Trees have more than 2 children per node. 
    - They traverse similarly to breadth first with a queue but looking for a list of k children instead of left and right
- Binary Search Tree is a special type of tree where the child with a smaller value than the root is placed to the left and the bigger child to the right. This allows us to just search down one side of the tree. 
- 
