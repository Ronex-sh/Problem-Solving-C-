# 📘 1D Array Problems

Practice problems for mastering **1D Arrays** in C++.

---

## 🧩 Problems Overview

| # | Problem | Difficulty | Core Idea |
|---|---------|------------|------------|
| 1 | [Find Most Frequent Number](./Problems.md#-1-find-most-frequent-number) | Medium | Frequency counting 
| 2 | [Smallest Pair](./Problems.md#-2-smallest-pair) | Easy | Minimum pair evaluation |
| 3 | [Digits Frequency](./Problems.md#-3-digits-frequency) | Medium |Digits frequency counting |

---

# 🔹 [1. Find Most Frequent Number](./find_most_frequent.cpp)

## 🎯 Goal

Given an array of integers, find the number that appears the most.

If multiple numbers have the same frequency, choose the **largest number**.

---

## 📌 Constraints

```text
1 <= N <= 200
-500 <= value <= 270
```

---

## ⚠️ Notes

- Do NOT use nested loops.
- Use frequency counting.
- Negative values are allowed.

---

## 💡 Example

### Input

```text
7
-1 2 -1 3 -1 5 5
```

### Output

```text
-1 repeated 3 times
```

---

## 🧠 Explanation

Frequency count:

```text
-1 → 3 times
 2 → 1 time
 3 → 1 time
 5 → 2 times
```

The highest frequency is `3`, so the answer is:

```text
-1
```

---

# 🔹 2. Smallest Pair

## 🎯 Goal

Find the minimum value of:

```text
A[i] + A[j] + j - i
```

Where:

```text
i < j
```

---

## 💡 Example

### Input

```text
4
2 0 1 9
```

### Output

```text
2
```

---

## 🧠 Explanation

Best pair:

```text
0 + 1 + (2 - 1)
= 2
```

---

# 🔹 [3. Digits Frequency](./Digits_Frequency.cpp)

## 🎯 Goal

Given `N` integers, count how many times each digit from `0` to `9` appears.

---

## 📌 Constraints

```text
1 <= N <= 200
```

---

## ⚠️ Notes

- Count digits inside all numbers.
- Digits may appear multiple times.
- Print the frequency for every digit from `0` to `9`.

---

## 💡 Example

### Input

```text
2
78 307
```

### Output

```text
0 1
1 0
2 0
3 1
4 0
5 0
6 0
7 2
8 1
9 0
```

---

## 🧠 Explanation

Digits found:

```text
7 → appears 2 times
8 → appears 1 time
3 → appears 1 time
0 → appears 1 time
```

All other digits appear `0` times.

---
# 🚀 Topics Covered

- Find Most Frequent Number
- Smallest Pair
- Digits Frequency
