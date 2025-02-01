Merge two sorted list
Algorithm:
Initialize a dummy node to serve as the starting point for the merged list.
Create a pointer current to traverse and build the new list.
Compare the elements from list1 and list2:
If the value of list1 is smaller, append it to the new list and move list1 pointer to the next node.
If the value of list2 is smaller, append it to the new list and move list2 pointer to the next node.
If one list is exhausted, append the remaining nodes of the other list to the merged list.
Return the next node of the dummy (since it's the start of the merged list).

Least frequently used cache
Algorithm:
Use a hash map to store key-value pairs and their frequency counts.
Use another hash map to store the keys for each frequency count.
For get(key), if the key exists, increment its frequency count and move it to the corresponding list of keys with the new frequency.
For put(key, value), if the cache is full, remove the least frequently used key.
Use a priority queue to track the least frequently used keys.
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Yyx6BftN)
