# insertion
Insertion Sort Algorithm
Insertion Sort is a simple comparison-based sorting algorithm that builds the final sorted array one item at a time. It is efficient for small data sets or when the input array is mostly sorted. The algorithm works by repeatedly inserting the current element into its correct position within the already sorted portion of the array.

Algorithm Steps
Input:

array: An array of elements to be sorted.
n: The number of elements in the array.
Sorting Process:

Iterate through the array starting from the second element (index 1) up to the last element (index n-1).
For each iteration:
Store the current element in the variable key.
Initialize j as the index of the element before the current element (i - 1).
Comparisons and Shifting:

While j is greater than or equal to 0 and the element at array[j] is greater than the key:
Shift the element at array[j] one position to the right (to array[j + 1]).
Decrement j by 1.
Placing the Element:

After the while loop, place the key at the correct position in the sorted portion of the array.
Insert the key at array[j + 1].
Repeat:

Continue iterating through the remaining unsorted elements, repeating the process of comparing and inserting.
Output:

Once the loop completes, the array will be sorted in ascending order.
Usage and Considerations
Insertion Sort is suitable for smaller arrays or when most of the array is already sorted, as it performs well in such cases.
The algorithm has an average and worst-case time complexity of O(n^2), making it less efficient for larger datasets compared to other sorting algorithms like Quick Sort or Merge Sort.
It is an in-place sorting algorithm, meaning it doesn't require additional memory for sorting.
Example
Consider the following example of how Insertion Sort works on an array:

Input array: [12, 11, 13, 5, 6]

Pass 1: [11, 12, 13, 5, 6]
Pass 2: [11, 12, 13, 5, 6]
Pass 3: [5, 11, 12, 13, 6]
Pass 4: [5, 6, 11, 12, 13]
The array is sorted incrementally after each pass until the final sorted array is achieved.

Conclusion
Insertion Sort is a simple and intuitive sorting algorithm that can be effective for small datasets or partially sorted data. While its time complexity may not be as efficient as other algorithms for larger arrays, it provides a good understanding of basic sorting techniques.





