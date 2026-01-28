# Prefix Sum (DSA)

This folder contains implementations of **Prefix Sum** techniques used to efficiently solve range-based array problems.

Prefix Sum helps reduce repeated calculations by preprocessing the array, allowing range sum queries to be answered in constant time.

---

## 📂 Files Overview

### 1️⃣ prefix__sum.py
**Problem:** Build a prefix sum array from a given array.

**Description:**
- Converts the original array into a prefix sum array
- Each index stores the sum of all elements up to that index

**Time Complexity:** O(N)  
**Space Complexity:** O(N)

---

### 2️⃣ prefixsum_lr.py
**Problem:** Find the sum of elements between index **L** and **R** using prefix sum.

**Description:**
- Uses the prefix sum array to calculate range sum efficiently
- Avoids looping between L and R

**Query Time Complexity:** O(1)  
**Preprocessing Time:** O(N)

---

### 3️⃣ prefixsum__queries.py
**Problem:** Answer multiple range sum queries efficiently.

**Description:**
- Builds prefix sum once
- Answers multiple `(L, R)` queries in constant time per query

**Time Complexity:** O(N + Q)  
- N → array size  
- Q → number of queries  

**Space Complexity:** O(N)

---

## 🧠 Key Formula

For a prefix sum array `prefix`:


- If `L == 0`
- sum = prefix[R]
---

## 🎯 Why Prefix Sum?

- Optimizes repeated range sum queries
- Commonly asked in **coding interviews**
- Used in:
- Subarray problems
- Frequency queries
- 2D matrix sum problems

---

## 🚀 Next Topics to Extend
- Subarray sum equals K
- Prefix sum with hash map
- 2D prefix sum (matrix)
- Sliding window vs prefix sum

---

📌 **Author:** Ganesh S  
📌 **Category:** Data Structures & Algorithms


