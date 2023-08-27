# Sorting algorithms

The file containing sorting algorithms quick overviews of basic sorting algorithms.

## Heapsort

**Overview:**
Heapsort is a comparison-based sorting algorithm that utilizes the concept of a max-heap. It involves transforming the input array into a max-heap, where the largest element is at the root. The root element is then swapped with the last element, which is removed from the heap. The heap is restructured to maintain the max-heap property, and the process repeats until the array is sorted.

**Time Complexity (average):** O(n*log(n)) \
**Space Complexity:** O(1)

## Insertion Sort

**Overview:**
Insertion Sort is a simple sorting algorithm that builds the final sorted array one item at a time. It starts with the second element and compares it with each previous element, moving elements as needed to insert the current element into its correct position.

**Time Complexity (average):** O(n^2) \
**Space Complexity:** O(1)

## Bubble Sort

**Overview:**
Bubble Sort is a straightforward sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. This process is repeated for each element until the entire array is sorted.

**Time Complexity (average):** O(n^2) \
**Space Complexity:** O(1)

## Merge Sort

**Overview:**
Merge Sort is a divide-and-conquer algorithm that divides the input array into two halves, sorts each half separately, and then merges the sorted halves to produce the final sorted array. It is known for its consistent performance and is suitable for large datasets.

**Time Complexity (average):** O(n*log(n)) \
**Space Complexity:** O(n)

## Quick Sort

**Overview:**
Quick Sort is an efficient sorting algorithm that relies on a pivot value to divide the input array into smaller segments. The algorithm selects a pivot element and arranges the array elements such that elements smaller than the pivot are on its left, and elements greater than the pivot are on its right. This process is recursively applied to the sub-arrays on both sides of the pivot until the entire array is sorted.

**Time Complexity (average):** O(n*log(n)) \
**Space Complexity:** O(log(n))

## Selection Sort

**Overview:**
Selection Sort is a simple sorting algorithm that repeatedly selects the smallest element from the unsorted part of the array and places it at the beginning of the sorted part. It maintains two sub-arrays within the main array: the sorted sub-array and the unsorted sub-array. In each iteration, it finds the smallest element in the unsorted sub-array and swaps it with the first element of the unsorted sub-array.

**Time Complexity (average):** O(n^2)) \
**Space Complexity:** O(1)

## Shell sort

**Overview:**
Shell Sort is an extension of the Insertion Sort algorithm that improves its performance by sorting elements at varying intervals. It starts by sorting elements that are distant from each other and gradually reduces the interval until the entire array is sorted. This helps move smaller elements to their correct positions faster, making the subsequent Insertion Sort steps more efficient.

**Time Complexity (average):** O(n*log^2(n)) \
**Space Complexity:** O(1)

## Counting sort

**Overview:**
Counting Sort is a non-comparison-based sorting algorithm that works best for sorting integers within a specific range. It creates a counting array to keep track of the frequency of each element in the input array. The counting array is then modified to store the positions where each element should appear in the sorted array. The elements are then placed in their correct positions in the output array based on the information in the counting array.

**Time Complexity (average):** O(n+k) \
**Space Complexity:** O(k)

## Bucket Sort

**Overview:**
Bucket Sort is a distribution-based sorting algorithm that works well when the input elements are uniformly distributed across a range. It divides the input range into a fixed number of equal-sized buckets, places elements into their respective buckets, and then sorts each bucket individually, either using another sorting algorithm or recursively applying bucket sort. Finally, the sorted buckets are concatenated to produce the sorted array.

**Time Complexity (average):** O(n + k)
**Space Complexity:** O(n)

## Radix Sort

**Overview:**
Radix Sort is a non-comparison-based sorting algorithm that processes elements digit by digit. It sorts numbers based on each digit's value, from the least significant digit to the most significant digit (LSD) or vice versa (MSD). Radix Sort can be applied to integers or strings by considering each character's ASCII value. It repeatedly distributes the elements into buckets based on the current digit and collects them back in order.

**Time Complexity (average):** O(n * k)
**Space Complexity:** O(n + k)



