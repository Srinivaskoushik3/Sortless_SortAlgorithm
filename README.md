# Sortless_SortAlgorithm
Implementation of sorting algorithms.
The SortlessSort_Algorithm repository consists of a C program that implements the "Sortless Sort" algorithm, a unique approach to sorting data without utilizing the traditional sorting phase. This innovative technique organizes data by alternatively distributing elements into two separate lists and merging them then in a balanced way. The project focuses on sorting an array of random 500 numbers which are generated and printed first hand. The algorithm works by recursive distribution which splits arrays into two sublists based on element positions and merge these sublists in order to obtain sorted arrays. After that sorting is done, program displays arrays before and after sorting process has been completed. This project places emphasis on an alternative sorting technique and shows how different ways can be employed for efficient data organization.



Initialization and Random Array Generation:

The array a is populated with 500 random numbers between 1 and 600. This part is correctly implemented.

sort Function:

This is the main function that recursively divides the array into smaller subarrays, sorts them, and then merges them back together. This is similar to how merge sort works.

merging Function:

This function merges two subarrays back together in sorted order, which is typical for the merge step in merge sort.
split Function:
