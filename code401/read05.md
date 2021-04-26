# Read 05

[Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)

[What's a Linked List, Anyway? 1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)

[What's a Linked List, Anyway? 2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)

## WHY
When you're looking to solve a problem, there are many ways to do so. You want to have an effective way to organize the data. One way is using Linked Lists.

## WHAT
Linked List: This is a linear data structure that contains nodes. These nodes are linked and point to the next node when Singly, and to next or previous node when Doubly.

Node: An individual item that lives in a linked list. There is data for each link. These are elements of the list.

Singly: This refers to the amount of references a node has. When it is Singly, it has one reference. It points to the next node.

Doubly: This refers to two references a node has. It points to a next and a previous node.

![Linked List](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/images/LinkedList1.PNG)

## HOW
Linked Lists are dynamic data structures. Being a dynamic data structure means it can shrink and grow in memory. There isn't a set amount of memory needed in order to exist. The size and shape can also change.

Linked Lists can vary in size. However, not matter how big, they always have a similar make up. They are made of nodes. The starting node is called a head. The head is the only entry point. The end of the Linked List is a node that points to null or empty value. "A node only knows about what data it contains, and who its neighbor is." This means that a node has two parts, the data and next.

You can grow a Linked List. They have non-contiguous memory which make them unique. They work like arrays. To grow your Linked List, you would find the head node; then make a new node, set the pointer to the current first node of the list; then rearrange the head node's pointer to point at the new node.

They are super helpful if you don't know the size of the list and want to add or remove things quickly. You don't have to worry about random access.

[<== Back](https://simoneodegard.github.io/reading-notes/)