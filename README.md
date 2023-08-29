# Project Title: C - Sorting Algorithms & Big O

## Overview


## Instructions:

1. Ensure a compiler is installed.
2. Clone the repository (Sorting algorithms) on your local machine.


## Definition of Project Terms

- **Bubble Sort Algorithm:** This works by repeatedly comparing adjacent elements in a list and swapping them if they are out of order. The algorithm gets its name from the way that smaller elements "bubble" to the top of the list as the algorithm iterates. This makes bubble sort easy to understand and implement, but it's not the most efficient sorting algorithm.


- **Insertion Sort Algorithm:** In this sort, the algorithm considers each element in the unsorted part of the list, one at a time. For each element, it compares it to the element that comes before it in the sorted part of the list. If the current element is smaller than the previous element, it stays in place.

Otherwise, it is swapped with the previous element, and the process continues until the current element is in its correct position. This is repeated for each element in the unsorted part of the list until the entire list is sorted.

To use the provided function, you must include the provided source and header files in your program. Then you can call the function by passing a pointer to the head of your doubly linked list. The function will traverse the list and swap the nodes to sort the list, without modifying the values in the nodes. Finally, the function will print the sorted list.

The time complexity of this type of algorithm depends on the order of the elements in the list. In the best case, when the list is already sorted, the alogrithm will take O(n) time to sort the list, where n is the number of elements in the list. In the average case, the algorithm will take O(n^2) time to sort the list, since it may need to traverse and swap elements multiple times to achieve the sorted order.


- **Selection Sort Algorithm:** This sorting Alogrithm finds the minimum element in the unsorted part of the array and swaps it with the first element in that part. This process is repeated until the entire array is sorted. This alogrithm is implemented in the function selection sort, which takes an integer array and its size as arguments. The function returns the sorted array.

First, include the provided source code and header files in your program to use the selection sort function. Then, call the function, by passing the integer array and its size as arguments. Finally, the function will sort the array and print the sorted array. Keep in mind that the program will also print that array after each swap operation for visualization.


The best-case time complexity of the selection sort Alogrithm is O(n^2), where n is the number of elements in the array. This is because the alogrithm performs the same number of comparisons and swaps regardless of the initial order of the elements.

In the average case, the time complexity is also O(n^2), due to the algorithms' repeated search for the minimum element.

Finally, the worst-case time complexity is also O(n^2), which occurs when the array is in reverse order.


## Acknowledgement
Thanks to the ALX community.


## Authors
- Ginika Elizabeth Nna
- Akoma Goodness James
