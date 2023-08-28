Project Title: C - Sorting algorithms & Big O

Overview

In this project, we will review different concept of sorting alogrithm and implementation through worst, average and best case scenario. We search and merge through linear or binary method, complexity( time and space), and runtime(Big O notation).

# instructions. 

1. Ensure there is a compiler installed.
2. clone repo to yoyr local machine.


Project Description

Bubble Sort Alogrithm: This works by repeatedly comparinf adjacent elements in a list and swapping them if they are out of order. The alogrithm gets its name from the way that smaller elements "bubble" to the top of the list as the alogrithm iterates. This makes bubble sort easy to understand and implement, but it's not the most efficient sorting alogrithm.


Insertion Sort Alogrithm for Doubly linked List.

In this sort, the alogrithm considers each element in the unsorted part of the list, one at a time. For each element, it compares it to the element that come before it in the sorted part of the list. If the current element is smaller than the previous element, it stays in place.

Otherwise, it is swapped with the previous element, and the process continues until the current element is in its correct position. This is repeated for each element in the unsorted part of the list, until the entire list is sorted.

To use the provided function, you must include the provided  source and header filea in your program. Then you can call the function by passing a pointer to the head of your doubly linked list. The function will tranverse the list and swap the nodes to sort the list, without modifying the values in the nodes. Finally, the function will print the sorted list.

The time complexity of this tyoe of alogrithm depends on the order of the elements in the list. In the best case, when the list is already sorted, the alogrithm will take O(n) time to sort the list, where n is the number of elements in the list. In the average case, the alogrithm will take O(n^2) time to sort the list, since it may need to traverse and swap elements multiple times to achieve the sorted order.
