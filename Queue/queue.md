# Queue
Queue is a **linear data structure** which operates in a *First IN First OUT* or *Last IN Last OUT*.

# Queue Operations
1. Enqueue() – Add item to the queue from the REAR.
2. Dequeue() – Remove item from the queue from the FRONT.
3. isFull() – Check if queue is full or not.
4. isEmpty() – Check if queue empty or not.
5. count() – Get number of items in the queue.

# Types of Queue
- Simple Queue
- Circular Queue
- Priority Queue

# Applications of Queue
- CPU scheduling, Disk Scheduling.
- Handling of interrupts in real-time systems. The interrupts are handled in the same order as they arrive, First come first served.
- In real life, Call Center phone systems will use Queues, to hold people calling them in an order, until a service representative is free.
- When data is transferred asynchronously between two processes. Queue is used for synchronization.

# Circular Queue
Circular Queue is a **linear data structure** in which the operations are performed based on *FIFO (First In First Out)*principle and the last position is connected back to the first position to make a circle. It is also called **‘Ring Buffer’**. It is a type of Queue data structure which overcomes some drawback of the simple queue data structure.

In a Linear queue, once the queue is completely full, it’s not possible to insert more elements. Even if we dequeue the queue to remove some of the elements, until the queue is reset, no new elements can be inserted. You must be wondering why?

=> When we dequeue any element to remove it from the queue, we are actually moving the front of the queue forward, thereby reducing the overall size of the queue. And we cannot insert new elements, because the rear pointer is still at the end of the queue. The only way is to reset the linear queue, for a fresh start.

# code
- [Linear Queue](LinearQueue.cpp)
- [Circular Queue](CircularQueue.cpp)

# 
[**Back to readme**](../README.md)