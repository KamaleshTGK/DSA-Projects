# 🎯 Selection Sort

Selection Sort repeatedly finds the **minimum element** from the unsorted part of the array and puts it at the beginning.

---

## ⚡ Algorithm Steps
1. Start from index `i = 0`.
2. Find the smallest element in the remaining array.
3. Swap it with `arr[i]`.
4. Increment `i` and repeat.

---

## ⏱️ Time Complexity
- Best Case: **O(n²)**
- Worst Case: **O(n²)**
- Space: **O(1)**

---

## 📌 Example
Input: `[64, 25, 12, 22, 11]`

Steps:
- Pass 1 → `[11, 25, 12, 22, 64]`  
- Pass 2 → `[11, 12, 25, 22, 64]`  
- Pass 3 → `[11, 12, 22, 25, 64]`  
- Pass 4 → `[11, 12, 22, 25, 64]` (sorted)  

Output: `[11, 12, 22, 25, 64]`

---

## ⚠️ Note
- Performs fewer swaps than Bubble Sort.
- Still not efficient for large datasets.

---

## 📂 Code
See `SelectionSortDemo.java` in this folder.
