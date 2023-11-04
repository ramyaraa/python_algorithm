# Sorting Algorithms

This repository contains implementations of various sorting algorithms. For now, we are focusing on the **Insertion Sort** algorithm. Sorting algorithms are an essential concept in computer science, used to arrange data in a specific order, typically ascending or descending.

---

## Insertion Sort

### Overview

Insertion Sort is a simple and intuitive sorting algorithm. It builds the sorted array (or list) one item at a time by comparing each new element with the already sorted ones and inserting it into its correct position. It works well for small datasets or datasets that are nearly sorted.

### How It Works

The algorithm divides the list into two parts: a sorted and an unsorted part. The algorithm repeatedly picks the first element from the unsorted part and inserts it into the correct position in the sorted part.

**Steps:**
1. Start with the second element in the array (consider the first element to be sorted).
2. Compare the current element with the elements in the sorted portion (left side).
3. Shift the elements in the sorted portion to the right until the correct position for the current element is found.
4. Insert the current element into its correct position.
5. Repeat the process for each element in the unsorted portion of the array.

### Time Complexity

- **Best Case:** O(n) – The array is already sorted.
- **Average Case:** O(n^2) – Randomly ordered array.
- **Worst Case:** O(n^2) – The array is in reverse order.

### Space Complexity

- **O(1)** – In-place sorting algorithm.

