# frontier
frontier with stack, queue and ordered queue.

### Stack and Queue
Stack and Queue are two of the most popular data structures. Both are linked lists, whereupon their mainly features are add and remove data off their list. These features will be to influence the data’s order, adding and removing the data. Both are used in a lot of applications, for example, pathfinding algorithms.
#### Stack
Stack, as known as last-in-first-out (LIFO) or first-in-last-out (FILO). The data are removed according to the input’s opposite order.
Complexity of add: O(1).
Complexity of remove: O(1).

#### Queue
Queue, as known as first-in-first-out (FIFO). The data are removed according to the input’s order.
Complexity of add: O(1).
Complexity of remove: O(1).

#### Ordered Queue
The simple structures, stack and queue, don’t need data with an associated value. However, when we are working with data that has associated values and we need to sort these data in real time, we insert the data in the list and can work with an ordered queue. 

**Simple form:** The simple form, we can insert the data at the correct position, according to the crescent or decrescent order, but this approach has a bad side when we are working with larger scale of data, then its complexity of remove is O(1), however, to add in order, the complexity is O(N).

**Heap list:** When we are working with larger scale of data, there are many strategies of sorting, but we can mention heap list, that its structure is a list/array, but, its logic is as a binary tree. Whereupon the tree’s height is approximately the order of O(log N), the complexity of add and remove data on heap list is O(log N).
