# 📝 SWE306 – Algorithm Analysis and Design
### 📅 Midterm Exam – 14.04.2025
**Teacher:**  Nur Banu OĞUR   
**Duration:** ~60 minutes  
**Format:** Written – 5 questions (mix of theory and analysis)  
**Tags:** `DivideAndConquer` `DynamicProgramming` `QuickSort` `TimeComplexity` `MasterTheorem` `GrowthRates`

---

## 📌 Questions

### 1. Difference Between Divide and Conquer vs Dynamic Programming
**Prompt:**  
Explain the difference between Divide and Conquer and Dynamic Programming strategies.
- Mention how each breaks the problem down
- Where overlapping subproblems apply
- List advantages and disadvantages of both

**Expected Points:**
- Clear definitions
- Use of memoization vs recursion tree
- Examples (like Merge Sort vs Matrix Chain Multiplication)
- Pros/cons comparison

---

### 2. Quick Sort: Best vs Worst Case Analysis
**Prompt:**
- Explain how best and worst cases occur in Quick Sort
- Provide time complexities using Θ notation
- Optionally, apply the Master Theorem if relevant

**Expected Points:**
- Best case: pivot always in the middle
- Worst case: already sorted list with bad pivot (first/last element)
- T(n) = T(n/2) + Θ(n) vs T(n−1) + Θ(n)

---

### 3. Step-by-Step Time Complexity Derivation
**Prompt:**  
Given an algorithm (similar to ones in lecture slides), perform a step-by-step mathematical analysis to determine its time complexity.

**Expected Points:**
- Recurrence relation derivation
- Use of iteration method or expansion
- Final closed-form expression (e.g., O(n log n))

---

### 4. Sort Time Complexities from Fastest to Slowest
**Prompt:**  
Sort the following functions in increasing order of growth:
```angular2html
1, log(log(n)), √n, n^(3/4), n*log(n), n!, 2^n
```


**Expected Points:**
- Use asymptotic notation knowledge
- Optional explanation of each step
- Correct ordering is enough for full marks

---

### 5. Master Theorem Applications
**Prompt:**  
Apply the Master Theorem to each given recurrence and find the time complexity.

**Examples:**
- T(n) = 2T(n/2) + Θ(n)
- T(n) = 3T(n/4) + Θ(n)
- T(n) = T(n/2) + Θ(1)

**Expected Points:**
- Identify a, b, f(n)
- Compare f(n) with n^log_b(a)
- Apply correct Master Theorem case
- Final Big-O result

---

## 🧠 Notes & Tips from Students

- Make sure to revise Master Theorem cases in detail (Case 1/2/3).
- Know how to spot overlapping subproblems for DP vs simple recursion for D&C.
- QuickSort's worst case is commonly asked – be ready to write recurrence T(n) = T(n-1) + Θ(n).
- Time complexity ordering questions are quick points if you’re familiar with function growth.






---

## 📩 Want to add your solution or exam memory?
> Fork the repo → Go to this file → Add below each question or under `Notes & Tips` → Make a pull request 💡  

