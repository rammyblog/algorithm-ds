## Binary Search

Binary search is an algorithm; its input is a sorted list of elements (I’ll explain later why it needs to be sorted). If an element you’re looking for is in that list, binary search returns the position where it’s located. Otherwise, binary search returns null.
In general, for any list of n, binary search will take log2n steps to run in the worst case, whereas simple search will take n steps.
Binary search only works when your list is in sorted order. For example, the names in a phone book are sorted in alphabetical order, so you can use binary search to look for a name. What would happen if the names weren’t sorted?

## Big O Notation

Big O notation is special notation that tells you how fast an algorithm is.

Some common Big O run timesHere are five Big O run times that you’ll encounter a lot, sorted from fastest to slowest:
•O(log n), also known as log time. Example: Binary search.
•O(n), also known as linear time. Example: Simple search.
•O(n\* log n). Example: A fast sorting algorithm, like quicksort (coming up in chapter 4).
•O(n2). Example: A slow sorting algorithm, like selection sort (coming up in chapter 2).
•O(n!). Example: A really slow algorithm, like the traveling salesperson (coming up next!).

For now, the main takeaways are as follows:
•Algorithm speed isn’t measured in seconds, but in growth of the number of operations.
•Instead, we talk about how quickly the run time of an algorithm increases as the size of the input increases.
•Run time of algorithms is expressed in Big O notation.
•O(log n) is faster than O(n), but it gets a lot faster as the list of items you’re searching grows.

Recap
•Binary search is a lot faster than simple search.
•O(log n) is faster than O(n), but it gets a lot faster once the list of items you’re searching through grows.
•Algorithm speed isn’t measured in seconds.
•Algorithm times are measured in terms of growth of an algorithm.
•Algorithm times are written in Big O notation
