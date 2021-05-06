# Read 15
[Trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

## Why
Using trees is a way to create a data structure that mimics a "yes/no" decision making process. [resource](https://www.i-programmer.info/babbages-bag/477-trees.html#:~:text=Binary%20trees&text=The%20importance%20of%20a%20binary,%2Fno%22%20decision%20making%20process.&text=Of%20course%20if%20the%20loop,only%20obscures%20the%20basic%20principles.)

## What

"Trees can have any number of children per node, but Binary Trees restrict the number of children to two (hence our left and right children)."

K-ary Trees: If nodes have more than 2 child nodes, then it is a K-ary Tree.

**Terms**
- **Node**: A component that may contain it's own value and references to the other node.
- **Root**: The node at the beginning of the tree
- **K**: The number that specifies the maximum number of children any node may have in a k-ary tree. K=2 for a binary tree
- **Left**: Reference to one child node in a binary tree
- **Right**: Reference to the other child node in a binary tree
- **Edge**: The link between a parent and child node
- **Leaf**: A node that does not have any children
- **Height**: The number of edges from root to the furthest leaf.

## How

### Traversals
**Depth First** Prioritizes going through the height of the tree first. The most common way to traverse through a tree is to use recursion.
  - **Pre-order** root > left > right
  - **In-order** left > root > right
  - **Post-order** left > right >root

**Pre-order**
![Pre-order](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/images/DepthTraversal11.PNG)
1. Root, A, is the output value
2. We will then look to the left, B
3. Look to the left of that last node which is a leaf, D. D would then get popped off
4. We look at the next leaf, E
5. Pop off B
6. Back to the root of A
7. Look at C
8. Look to the F
9. Pop off F
10. Pop off C
11. Back to the root of A

**Breadth First** Iterates through the tree going through each level of the tree node by node. Traversal uses a queue.
1. Root, A, is in the queue and needs to be dequeued.
2. Enqueue left, B, and right, C, child.
3. You then dequeue the front nodes (B then C).
4. Continue the enqueue and dequeue process on with the leafs

[<== Back](https://simoneodegard.github.io/reading-notes/)