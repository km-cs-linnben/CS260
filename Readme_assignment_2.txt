1.	Based on what we know about linked lists, stacks, and queues, design a queue data structure:
1.	What functions are we likely to need for a queue to function like the one discussed in class?

We would need a function to remove an object from the front of the queue and another to add to the back
of the queue. Perhaps some others to find the length of the queue and the values of each object in the queue.

2.	What values will we need to know about the structure for our queue to function properly?

We would need to know the values of the front and rear objects in the queue in particular. Also, which object
is the front and which is the rear. The number of objects in the queue would be useful as well. For testing
you could make sure the length of queue is changing when performing add/remove functions.

2.	Based on what we know about linked lists, design a list data structure that allows us to add (insert) or remove (delete) values at a given location in the list (instead of the top of a stack or the front or back of a queue):
1.	What functions are we likely to need for a list to function like this?

We would need a function to add/remove to or from the front, another to add/remove to/from the back, and one
more to add/remove to/from a specific location. You would create a node object that holds a value and a
pointer to the next object in the list. The last object in the list would have a pointer to null. You would
have another pointer to the first object in the list. To add to the front, you would need to change the head
pointer to the new object. To add to the back you would need the new object have a pointer to null and change
the now second to last objects pointer to point to the newly added object. And lastly for the middle you would
need to change the pointer of the object ahead of it in the list to point to the newly added object.

2.	What values will we need to know about the structure for our list to function properly?

You would need the memory locations of each node in the list, and specifically which node is the front and rear.
