# 🫧 Bubble Sort

Bubble Sort is a simple sorting algorithm where adjacent elements are repeatedly compared and swapped if they are in the wrong order.  
After each pass, the largest element "bubbles up" to the end.

---

## ⚡ Algorithm Steps
1. Traverse the array.
2. Compare each pair of adjacent elements.
3. Swap if they are in the wrong order.
4. Repeat until no swaps are needed.

---

## ⏱️ Time Complexity
- Best Case: **O(n)** (already sorted, 1 pass)
- Worst Case: **O(n²)**
- Space: **O(1)**

---

## 📌 Example
Input: `[9, 1, 6, 3, 7]`

Steps:
- Pass 1 → `[1, 6, 3, 7, 9]`  
- Pass 2 → `[1, 3, 6, 7, 9]`  
- Pass 3 → `[1, 3, 6, 7, 9]` (sorted)  

Output: `[1, 3, 6, 7, 9]`

---

## ⚠️ Note
- Bubble Sort is **not efficient** for large datasets.
- Useful for teaching the concept of swapping.

---

## 📂 Code
See `BubbleSortDemo.java` in this folder.
