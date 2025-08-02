# DSA-Mastery-375

 
Welcome to **DSA-Mastery-375**, your complete roadmap to master Data Structures and Algorithms in **30 Days**. This repository contains a **curated list of 375 essential DSA problems** covering all major topics, with **clean Python solutions** and **concise theory revision** for each concept.

---

## 📌 Topics Covered

1. Arrays
2. Strings
3. Searching & Sorting
4. 2D Arrays / Matrix
5. Linked List
6. Stacks & Queues
7. Greedy Algorithms
8. Backtracking
9. Trees & Binary Trees
10. Binary Search Trees (BST)
11. Heaps & Hashing
12. Graphs
13. Dynamic Programming (DP)
14. Tries
15. Bit Manipulation
16. Segment Trees + Revision

---
 

## 📅 30-Day Structured Plan

| Day Range | Topics                        | Approx Qs | Difficulty Split |
| --------- | ----------------------------- | --------- | ---------------- |
| Day 1–3   | Arrays                        | \~45      | Easy–Medium      |
| Day 4–5   | Strings                       | \~30      | Easy–Medium      |
| Day 6–7   | Searching & Sorting           | \~25      | Easy–Medium–Hard |
| Day 8     | 2D Arrays / Matrix            | \~15      | Easy–Medium      |
| Day 9–10  | Linked List                   | \~30      | Easy–Medium      |
| Day 11–12 | Stacks & Queues               | \~30      | Easy–Medium–Hard |
| Day 13    | Greedy Algorithms             | \~15      | Medium           |
| Day 14–15 | Backtracking                  | \~20      | Medium–Hard      |
| Day 16–18 | Trees & Binary Trees          | \~30      | Easy–Medium–Hard |
| Day 19    | Binary Search Trees (BST)     | \~20      | Medium–Hard      |
| Day 20    | Heaps & Hashing               | \~20      | Easy–Medium      |
| Day 21–23 | Graphs                        | \~30      | Medium–Hard      |
| Day 24–27 | Dynamic Programming (DP)      | \~40      | Medium–Hard      |
| Day 28    | Tries                         | \~5       | Medium           |
| Day 29    | Bit Manipulation              | \~10      | Medium–Hard      |
| Day 30    | Segment Tree + Final Revision | \~10      | Hard + Wrap-Up   |

---

## 🔍 Folder Structure

```bash
DSA-Mastery-375/
│
├── Arrays/
│   ├── theory.md
│   ├── 01_find_min_max.py
│   └── ...
├── Strings/
├── SearchingSorting/
├── Matrix2D/
├── LinkedList/
├── StackQueue/
├── Greedy/
├── Backtracking/
├── Trees_BinaryTrees/
├── BST/
├── Heaps_Hashing/
├── Graphs/
├── DP/
├── Tries/
├── BitManipulation/
├── SegmentTrees/
└── README.md
```

---

## 🧠 Theory + Practice Format

Each topic contains:

* **theory.md**: Concepts, use-cases, diagrams, and complexity
* **Python code**: Problem-wise code files with comments and explanations

Example (from Arrays):

```python
# Problem: Find Maximum and Minimum in an Array
# Time: O(n), Space: O(1)

def find_min_max(arr):
    min_val = max_val = arr[0]
    for num in arr:
        if num < min_val:
            min_val = num
        elif num > max_val:
            max_val = num
    return min_val, max_val

# Example
print(find_min_max([3, 1, 7, 4, 2]))  # Output: (1, 7)
```

---

## 📚 Theory Included

Each topic folder contains a **`theory.md`** with:

* ✅ Definitions
* ✅ Key concepts & applications
* ✅ Diagrams, flowcharts, graphs
* ✅ Time and space complexities
* ✅ Use cases in real-life tech problems

---

## 🏆 Why This Sheet?

* Designed for **FAANG-level preparation**
* Covers all core CS concepts required in interviews
* Tested in real hiring environments
* Each question is solved **10 times with pen & paper** to ensure mastery

---

## 🛠️ Tech Stack

* Language: **Python**
* Version: 3.10+
* Tools: Git, VS Code

---

## 🙌 Contributions

Pull requests and issue reports are welcome! Feel free to fork and extend with Java/C++ solutions, visualizations, or notes.

---

## ⭐ Star this repo if you find it helpful!

Let’s master DSA together and crack that dream job! 💼💻
