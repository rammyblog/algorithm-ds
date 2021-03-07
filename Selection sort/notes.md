Reading an array take O(1) (constant time)
Inserting into an array takes O(n)(Linear time)
Deleting an element takes O(n)(Linear time)

Reading a Linked List take O(n) (linear time)
Inserting into an linked list takes O(1)(constant time)
Deleting an element takes O(1)(constant time)


What’s better if you want to insert elements in the middle: arrays or lists? With lists, it’s as easy as changing what the previous element points to. But for arrays, you have to shift all the rest of the elements down.
And if there’s no space, you might have to copy everything to a new location! Lists are better if you want to insert elements into the middle.

What if you want to delete an element? Again, lists are better, because you just need to change what the previous element points to. With arrays, everything needs to be moved up when you delete an element.

There are two different types of access: random access and sequential access. 
Sequential access means reading the elements one by one, starting at the first element. Linked lists can only do sequential access. If you want to read the 10th element of a linked list, you have to read the first 9 elements and follow the links to the 10th element. Random access means you can jump directly to the 10th element. You’ll frequently 
hear me say that arrays are faster at reads. This is because they provide random access. A lot of use cases require random access, so arrays are 
used a lot.

Exercise
2.2 Linked list
2.3 Array
2.4 The downside is the memory issue, And if there’s no space, you might have to copy everything to a new location!.
2.5  O(1) Slower2


Recap
• Your computer’s memory is like a giant set of drawers.
• When you want to store multiple elements, use an array or a list.
• With an array, all your elements are stored right next to each other.
• With a list, elements are strewn all over, and one element stores 
the address of the next one.
• Arrays allow fast reads.
• Linked lists allow fast inserts and deletes.
• All elements in the array should be the same type (all ints, 
all doubles, and so on).