# C - Sorting algorithms & Big O

## About / synopsis
An introduction to implementing multiple sorting algorithms separately, with -O text files for each algorithm listing their time complexity

## Built By

* [Robert Rowe]
* [Brett Davis]

## Built With

* [c] - Betty formatting

### Project contents

| File Name | Short Description |
| --- | --- |
|0-bubble_sort.c|An inefficient sorting algorithm that repeatedly swaps two values, the 'cursor' moving from left to right until the array is sorted|
|1-insertion_sort_list.c|A stable sorting algorithm that is efficient with small data sets and works by inserting a new node into the correct position of a pre-sorted array|
|2-selection_sort.c|Noted for simplicity, this algorithm typically performs worse than insertion sort, but has some performance advantages. It works by finding the smallest array item and adding it to the end of the sorted area of the array|
|3-quick_sort.c|Noted for being, as the name implies, significantly quicker than its main competitor algorithms.|
|100-shell_sort.c|An optimization of insertion sort, shell sort works as a compromise between inserting and swapping by moving elements long distances towards their correct area, and then swapping to achieve a sorted list|
|101-cocktail_sort_list.c|A sorting algorithm very similar to bubble sort, but instead of the 'cursor' only moving left to right, it moves both directions|
|102-counting_sort.c|Counting sort is an integer sorting algorithm that sorts by using key values as indexes|
|103-merge_sort.c|***|
|104-heap_sort.c|Heap sort is sometimes thought of as an improved selection sort, and works by maintaining the unsorted data in a heap data structure, to improve the time it takes to find the largest element|
|105-radix_sort.c|Radix sort is an algorithm that does not compare, but instead creates and distributes elements according to their radix|
|106-bitonic_sort.c|***|
|107-quick_sort_hoare.c|***|
|1000-sort_deck.c|In this task, the insertion sort algorithm was chosen due to ease of implementation and the consistent, somewhat small data set. It works by sorting first by suit, then by value|