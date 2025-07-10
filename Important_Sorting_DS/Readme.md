# 🔢 Sorting Algorithms Comparison

This repository contains implementations and a detailed comparison of popular sorting algorithms:

- Bubble Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Selection Sort
- Tim Sort

---

## 📊 Algorithm Comparison Table

| Algorithm       | Time Complexity (Best / Avg / Worst) | Space Complexity | Stable | Adaptive | Efficiency Rank | Advantages                                                                 | Disadvantages                                                                 |
|----------------|----------------------------------------|------------------|--------|----------|------------------|----------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| **Bubble Sort**    | O(n) / O(n²) / O(n²)                  | O(1)             | ✅ Yes | ✅ Yes   | 🥉 6th            | Simple to implement, good for teaching basics                              | Very slow on large datasets                                                   |
| **Insertion Sort** | O(n) / O(n²) / O(n²)                  | O(1)             | ✅ Yes | ✅ Yes   | 🥉 5th            | Fast for small or nearly sorted arrays                                     | Not efficient on large datasets                                               |
| **Selection Sort** | O(n²) / O(n²) / O(n²)                 | O(1)             | ❌ No  | ❌ No    | 🥉 4th            | Easy to implement, does minimal number of swaps                            | Always O(n²), slow regardless of input                                        |
| **Merge Sort**     | O(n log n) / O(n log n) / O(n log n)  | O(n)             | ✅ Yes | ❌ No    | 🥈 2nd            | Consistent performance, stable, good for linked lists                      | Uses extra memory, not in-place                                               |
| **Quick Sort**     | O(n log n) / O(n log n) / O(n²)       | O(log n)         | ❌ No  | ❌ No    | 🥇 1st            | Very fast on average, in-place sorting                                     | Not stable, can degrade to O(n²) without precautions                         |
| **Tim Sort**       | O(n) / O(n log n) / O(n log n)        | O(n)             | ✅ Yes | ✅ Yes   | 🥇 1st (Real-World) | Built-in sort in Python & Java, very efficient for real-world data         | Complex to implement manually, uses extra memory                             |

---

## 🧠 Key Concepts

### 🔄 Adaptive vs Non-Adaptive

| Term          | Definition                                                                 |
|---------------|----------------------------------------------------------------------------|
| **Adaptive**  | Takes advantage of existing order in the input to improve performance.     |
| **Non-Adaptive** | Treats all inputs the same regardless of order.                           |

**Examples:**
- Adaptive: Insertion Sort, Bubble Sort, Tim Sort
- Non-Adaptive: Selection Sort, Merge Sort, Quick Sort

---

### ⚖️ Stable vs Non-Stable

| Term         | Definition                                                                 |
|--------------|----------------------------------------------------------------------------|
| **Stable**   | Maintains the relative order of equal elements.                            |
| **Non-Stable** | Equal elements may change order after sorting.                            |

**Examples:**
- Stable: Insertion Sort, Merge Sort, Tim Sort
- Non-Stable: Quick Sort, Selection Sort

---

## 📁 Repository Contents

- `bubble_sort.py`
- `insertion_sort.py`
- `selection_sort.py`
- `merge_sort.py`
- `quick_sort.py`
- `tim_sort.py`
- `README.md` ← you're here!

---

## ✅ Use Cases

- Educational purposes
- Interview preparation
- Algorithm performance comparison
- Real-world sorting logic reference (e.g. Tim Sort)

---

## 👨‍💻 Contributions

Feel free to contribute optimized versions, visualizations, or language ports!

---

## 📜 License

This project is licensed under the MIT License.
