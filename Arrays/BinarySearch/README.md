# ⚡ Binary Search

Binary Search is an efficient algorithm to find an element in a **sorted array**.  
It repeatedly divides the search interval in half.

---

## ⚡ Algorithm Steps
1. Find the middle element.
2. If mid == target → found.
3. If target < mid → search left half.
4. If target > mid → search right half.
5. Repeat until low > high.

---

## ⏱️ Time Complexity
- Best Case: **O(1)**
- Worst Case: **O(log n)**
- Space: **O(1)**

---

## 📌 Example
Input: `[10, 20, 30, 40, 50]`, target = `40`  
Steps:
- mid = 2 → arr[2] = 30 → target > 30 → search right  
- mid = 3 → arr[3] = 40 → found  

Output: `Found at index 3`

---

## ⚠️ Note
- Works **only on sorted arrays**.
- Be careful with mid calculation:  
  `mid = low + (high - low) / 2` (to avoid integer overflow).

---

## 📂 Code
See `BinarySearchDemo.java` in this folder.
