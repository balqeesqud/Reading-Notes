# Stacks and Queues: Understanding Data Structures


## WHY:

In computer science, managing data efficiently is crucial for various applications. Stacks and queues are two 
fundamental data structures that help in organizing and manipulating data in specific ways to cater to different
scenarios.


## WHAT:

**Stack:**
A stack is a linear data structure that follows the Last-In-First-Out (LIFO) principle. Think of it like a stack of 
plates, where you can only add or remove the topmost plate. The last item added is the first one to be removed. Stacks 
are used in scenarios like tracking function calls in a program, backtracking in algorithms, and managing undo/redo 
functionality.

**Queue:**
A queue is another linear data structure, but it follows the First-In-First-Out (FIFO) principle. Imagine standing in
a queue; the person who joins first gets served first. Queues are used in scenarios like managing tasks in a printer 
queue, BFS (breadth-first search) traversal in graphs, and handling asynchronous tasks.


## HOW:

**Stack:**

    Push: To add an item to the top of the stack, you perform a "push" operation.
    Pop: To remove the topmost item from the stack, you perform a "pop" operation.
    Peek: To look at the top item without removing it, you use the "peek" operation.

Common implementations: Arrays, linked lists. You can use built-in data structures like Java's java.util.Stack or Deque.

**Queue:**

    Enqueue: To add an item to the back of the queue, you perform an "enqueue" operation.
    Dequeue: To remove the front item from the queue, you perform a "dequeue" operation.
    Front: To see the front item without removing it, you check the "front."

Common implementations: Arrays, linked lists. Java provides java.util.Queue interface and implementations like
LinkedList and ArrayDeque.

In summary, stacks and queues provide efficient ways to manage data based on specific access patterns. Stacks are 
suitable for managing function calls, undo/redo, and tracking state, while queues are ideal for managing tasks, 
BFS traversal, and managing asynchronous operations.