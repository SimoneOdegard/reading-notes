# Read 10
[Implementation: Stacks and Queues](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)

## Why
Stacks and queues allow us to store and retrieve data sequentially.

## What
**Stack** A stack is a data structure of Nodes. Each Node references the next Node in the stack, but not the previous Node. It follows the FILO (first in last out) and LIFO (last in first out) concept.

**Queue** Queue also follows the FILO (first in last out) and LIFO (last in first out) concept.

**Additional Terms**
- **push** when you put nodes or items into the stack
- **pop** when you remove nodes or items. Removing items from a stack means it is popped.
- **top** top of the stack
- **peek** the view of the value of the top.
- **isEmpty** if stack empty return true, else return false.
- **Peek O(1)** when you inspect the top node of the stack. Check with isEmpty
- **enqueue** nodes or items added to the queue
- **dequeue** nodes or items removed from queue
- **front** front/first node of the queue
- **rear** rear/last node of the queue

## How
**Pushing** Pushing a node onto a stack is called a O(1) operation. It will take the same amount of time no matter what. When you add a node, you are pushing into the stack from the top. The next property will be the value of the original top.

**Steps**
1. Have a node you want to add
1. Assign the next property to reference the same node that top is referencing. Top is the node on top of the stack
1. The new node is added to the stack but you need to indicate that it is now the first node. Re-assign our reference top to the new node then you're done!

**Popping**
Popping a node is removing it from the top. Remember, this is following FILO/LIFO. When you pop, the node is re-assigned to the node that lives below the top. Check the stack with isEmpty first before popping. You don't want a exception to be raised.

**Steps**
1. Create a reference named temp that points to the same node that top points to
1. Reassign top to the value of the next node
1. Clear out the next property in the temp node then remove it
1. Return the value of the temp node that was popped

**Enqueue** O(1) is how to add an item to the queue. Like pushing, it takes the same amount of time no matter what lives in the queue.

**Steps**
1. Change the next property of the rear node to point to the new node being added. Use rear.next
1. Re-assign the rear reference to point to the new node and you're done.

**Dequeue** Use when you want to remove an item from the queue. Again, use O(1). You will always remove the front node of the queue.

**Steps**
1. Made the front node have a temporary reference of temp.
1. Re-assign front to the next node in the queue
1. Reassign the next property on the temp node to be null. You have to properly clear unnecessary references
1. Return the value of the temp node that was removed

[<== Back](https://simoneodegard.github.io/reading-notes/)