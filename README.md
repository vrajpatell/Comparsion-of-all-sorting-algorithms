# Comparsion-of-all-sorting-algorithms

Sorting Algorithm 
This Program implements and compares following sorting algorithms:
1. Mergsort 		O(n log(n))
2. Heapsort		O(n log(n))
3. Quicksort		O(n^2)
4. Quicksort(3-median)	O(n log(n))
5. Insertion sort		O(n^2)
6. Selection sort		O(n^2)
7. Bubble sort		O(n^2)

Mergsort: - It is an O(n log(n)) comparison based sorting algorithm which is a Divide and conquer algorithm. It divides the input array into two halves, calls itself for the two halves, then merges the two sorted halves. 
Heapsort: - It is an O(n log(n)) comparison based sorting technique based on Binary Heap data structure. It is like selection sort where we first find the 	maximum element and place the maximum element at the end. The process is repeated for remaining elements.
Quicksort: - Quicksort is a Divide and Conquer algorithm which picks an element as pivot and partitions the given array around the picked pivot. The key 	process in QuickSort is partition (). It is having O(n^2) time complexity.
Quicksort(3-median): - Quicksort with three median uses the median of first, last and middle element as the pivot. It is done to avoid the worst case of quick sort in which time complexity is O(n^2). Quicksort with three median method has a complexity of O(n log(n)).
Insertion sort: - It is a simple sorting algorithm that works in similar way as you sort playing cards in your hands. Array of elements is sorted into two parts sorted and unsorted part. Values from unsorted part are picked and place at the correct position in the sorted part. It has run time complexity of O(n^2).
Selection sort: - It sorts an array by repeatedly finding the minimum element from unsorted array and putting it at the beginning. In every iteration of selection sort, the minimum element from unsorted array is picked and moved to the sorted array. It has complexity of O(n^2).
Bubble sort: - Bubble sort is the simplest sorting Algorithm that works by repeatedly swapping the adjacent elements if they are in wrong order. It has run time complexity of O(n^2).

In this program all the sorting algorithms are compared in three ways: - 
1. Random input is given to array using randomGenerator() function.
2. Nearly sorted input is given to array for sorting.
3. Reversely sorted input is given to array for sorting.

All the sorting algorithms perform above three task and from which start time and finish time of sorting is calculated. This helps us to find which sorting algorithm works optimal in all the three conditions given as array input.

Procedure to Run file in IDE: -
1. Place the sorting folder in your directory and open it in using any java supported IDE (NetBeans, Eclipse).
2. Execute the program.
3. It will ask “please enter the array size” as a input, Enter 500, 1000 as a input for array size.
4. It executes code and display first time taken in random input of array, second part will show array which is nearly sorted, and third part will show reversely sorted input array.
5. All sorting algorithms will give output in milliseconds which is used for comparison purpose of run time of each algorithm.

Procedure to Run file in command prompt: -
1. Open command prompt window and go to the directory where program is saved in system.
2. Then, type “javac sorting.java” and enter to compile the code.
3. After that type “java sorting” to execute the code.
4. It will ask “please enter the array size” as a input, Enter 500, 1000 as a input for array size.
5. It executes code and display first time taken in random input of array, second part will show array which is nearly sorted, and third part will show reversely sorted input array.
6. All sorting algorithms will give output in milliseconds which is used for comparison purpose of run time of each algorithm.
 
