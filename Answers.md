1. What are the order of insertions/removals for the following data structures?

* I like to refer Stack and Queues to an array. They are both a container of objects that are inserted and removed. The difference is that when removing an object from the container of a Stack. When pushing(inserting) objects they stack up on top of each other so when you want to pop(remove) an object the last object that was inserted will be popped/removed (Last in First out). On a Queue, inserting is the same as a Stack but removing is different. Instead of removing the last object that was pushed in last, the First object of the Queue will be removed (First in First out).

2. What is the retreival time complexity for the following data structures?

  * Linked List - O(n)
  * Hash Table - O(1)
  * Binary Search Tree - O(log(n))

3. What are some advantages to using a Hash Tables over an array in JavaScript?

  *A hash table is O(1) and an array is O(n). I believe an array can be O(1) also but only if you knew the index number of the item that you are looking for in the array but when you have a logn array that can be hard. So to search for the item in a array, you would have to iterate through it and compare each item if it matches your value(item you are looking for). For a hash table, you use the a key/property to retrieve the item or value that you are looking for. Hash tables look more neat and organized, as an array it can get messy as it grows.