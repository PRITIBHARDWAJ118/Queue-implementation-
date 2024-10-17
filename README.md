# Queue-implementation-
## Aim:
To study and implement queue using arrays.
## Theory:
A queue is a linear data structure that follows the First In, First Out (FIFO) principle, meaning that the first element added is the first one to be removed.

1. Basic Operations:
* Enqueue: Adds an element to the rear of the queue.
* Dequeue: Removes and returns the element from the front of the queue.
* Peek/Front: Returns the element at the front without removing it.
* isEmpty: Checks whether the queue is empty.
* isFull: Checks whether the queue is full (in the case of array implementation).

2. Queue Using Array:
* Fixed Size: In the array implementation, the size of the queue is fixed, and a maximum size (capacity) must be predefined.
* Index Tracking: Two pointers are used, front (points to the element at the front of the queue) and rear (points to the last element inserted).
    - Initially, both front and rear are set to -1.
    - As elements are enqueued, rear is incremented.
    - As elements are dequeued, front is incremented.
