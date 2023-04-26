0x1B. C - Sorting algorithms & Big O
--------------------------------------------------------------------------------------------------------
Learning Objectives: At least four different sorting algorithms, What is the Big O notation, and how to evaluate the time complexity of an algorithm? How to select the best sorting algorithm for a given input? What is a stable sorting algorithm?
Requirements
--------------------------------------------------------------------------------------------------------------------------------------Allowed editors: vi, vim, emacs, All files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89, All your files should end with a new line, A README.md file, at the root of the folder of the project, is mandatory, Code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl, Not allowed to use global variables, No more than 5 functions per file, Unless specified otherwise, you are not allowed to use the standard library. Any use of functions like printf, puts, … is totally forbidden. The prototypes of all your functions should be included in your header file called sort.h, Don’t forget to push your header file, All header files should be include guarded, A list/array does not need to be sorted if its size is less than 2
Task 0. Bubble sort
------------------------------------------------------------------------------------------------------------------------------------
Write a function that sorts an array of integers in ascending order using the Bubble sort algorithm
Prototype: void bubble_sort(int *array, size_t size); Expected to print the array after each time you swap two elements, Write in the file 0-O, the big O notations of the time complexity of the Bubble sort algorithm, with 1 notation per line:
Repo: GitHub repository: sorting_algorithms File: 0-bubble_sort.c, 0-O
Task 1. Insertion sort
---------------------------------------------------------------------------------------------------------------------------------
Write a function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm
Prototype: void insertion_sort_list(listint_t **list); Not allowed to modify the integer n of a node. You have to swap the nodes themselves. Expected to print the list after each time you swap two elements. Write in the file 1-O, the big O notations of the time complexity of the Insertion sort algorithm, with 1 notation per line
Repo: GitHub repository: sorting_algorithms File: 1-insertion_sort_list.c, 1-O
Task 2. Selection sort
--------------------------------------------------------------------------------------------------------------------------------------
Write a function that sorts an array of integers in ascending order using the Selection sort algorithm
Prototype: void selection_sort(int *array, size_t size); Expected to print the array after each time you swap two elements. Write in the file 2-O, the big O notations of the time complexity of the Selection sort algorithm, with 1 notation per line:
Repo: GitHub repository: sorting_algorithms File: 2-selection_sort.c, 2-O
Task 3. Quick sort
--------------------------------------------------------------------------------------------------------------------------------
Write a function that sorts an array of integers in ascending order using the Quick sort algorithm
Prototype: void quick_sort(int *array, size_t size); implement the Lomuto partition scheme. The pivot should always be the last element of the partition being sorted. Expected to print the array after each time you swap two elements. Write in the file 3-O, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line
Repo: GitHub repository: sorting_algorithms File: 3-quick_sort.c, 3-O
Task 4. Shell sort - Knuth Sequence
-------------------------------------------------------------------------------------------------------------------------------
Write a function that sorts an array of integers in ascending order using the Shell sort algorithm, using the Knuth sequence
Prototype: void shell_sort(int *array, size_t size); use the following sequence of intervals (a.k.a the Knuth sequence), Expected to print the array each time you decrease the interval. No big O notations of the time complexity of the Shell sort (Knuth sequence) algorithm needed - as the complexity is dependent on the size of array and gap
Repo: GitHub repository: sorting_algorithms File: 100-shell_sort.c
Task 5. Cocktail shaker sort
-----------------------------------------------------------------------------------------------------------------------------
Write a function that sorts a doubly linked list of integers in ascending order using the Cocktail shaker sort algorithm
Prototype: void cocktail_sort_list(listint_t **list); Not allowed to modify the integer n of a node. You have to swap the nodes themselves. Expected to print the list after each time you swap two elements. Write in the file 101-O, the big O notations of the time complexity of the Cocktail shaker sort algorithm, with 1 notation per line
Repo: GitHub repository: sorting_algorithms File: 101-cocktail_sort_list.c, 101-O
Task 6. Counting sort
--------------------------------------------------------------------------------------------------------------------------------
Write a function that sorts an array of integers in ascending order using the Counting sort algorithm
Prototype: void counting_sort(int *array, size_t size); You can assume that array will contain only numbers >= 0, Allowed to use malloc and free for this task, Expected to print your counting array once it is set up. This array is of size k + 1 where k is the largest number in array. Write in the file 102-O, the big O notations of the time complexity of the Counting sort algorithm, with 1 notation per line:
Repo: GitHub repository: sorting_algorithms File: 102-counting_sort.c, 102-O
Task 7. Merge sort
------------------------------------------------------------------------------------------------------------------------------------
Write a function that sorts an array of integers in ascending order using the Merge sort algorithm
Prototype: void merge_sort(int *array, size_t size); implement the top-down merge sort algorithm
When you divide an array into two sub-arrays, the size of the left array should always be <= the size of the right array. i.e. {1, 2, 3, 4, 5} -> {1, 2}, {3, 4, 5} Sort the left array before the right array. Allowed to use printf, Allowed to use malloc and free only once (only one call), Write in the file 103-O, the big O notations of the time complexity of the Merge sort algorithm, with 1 notation per line
Repo: GitHub repository: sorting_algorithms File: 103-merge_sort.c, 103-O
Task 8. Heap sort
--------------------------------------------------------------------------------------------------------------------------------------
Write a function that sorts an array of integers in ascending order using the Heap sort algorithm
Prototype: void heap_sort(int *array, size_t size); implement the sift-down heap sort algorithm
You’re expected to print the array after each time you swap two elements (See example below)
Write in the file 104-O, the big O notations of the time complexity of the Heap sort algorithm, with 1 notation per line
Repo: GitHub repository: sorting_algorithms File: 104-heap_sort.c, 104-O
Task 9. Radix sort
-------------------------------------------------------------------------------------------------------------------------------
Write a function that sorts an array of integers in ascending order using the Radix sort algorithm
Prototype: void radix_sort(int *array, size_t size); implement the LSD radix sort algorithm. You can assume that array will contain only numbers >= 0; Allowed to use malloc and free for this task. Expected to print the array each time you increase your significant digit (See example below)
Repo: GitHub repository: sorting_algorithms File: 105-radix_sort.c
