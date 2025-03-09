a singly linked list is a concrete data structure consisting of a sequence of nodes, starting from a head pointer.
	Each node stores:
		-element value(data)
		-link to the next node(pointer)
	![[Pasted image 20250201212223.png]]
	One of the key advantages to a singly linked list is that you can insert in the Beginning, end, or even in the middle.

//you can initialize a linked list by writing:
`LinkedList myList = new LinkedList();`

-pros: linked lists are very flexible in turns adding or removing elements.
-cons: you have to iterate throw it which makes reading elements slow, you can only iterate from the beginning(head) of the list which makes finding elements from the middle or at the end of the list very slow