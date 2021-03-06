# Linked Lists

See `py05_linked-list`

A linked list is a linear data structure where each element in a list is contained in a self-referential **node** object. 

**Self-referential** means nodes store a value (self), and a pointer to the next node (referential). 

* **Singly linked list** - Each node stores a pointer to the next node.
* **Doubly linked list** - Each node stores a pointer to the previous and the next node. 

The first node in a linked list is the **head**. The last node is the **tail**. The list only maintains a reference to the head (and sometimes tail) node - and not to every node. 

The last node has no next pointer, which is how the language knows it's the end of the list.

