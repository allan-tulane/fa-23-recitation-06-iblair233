# CMPS 2200 Recitation 06
## Answers

**Name:** Izzy Blair



Place all written answers from `recitation-07.md` here for easier grading.



- **2)**
The work is W(n) = W(n-1) + W(n-2) + O(1).
- **3)**
The span is W(n) = W(n-1) + W(n-2) + O(1). Solution: O(2^n).
- **4)**
It shows that some Fibonacci solutions are being calculated repeatedly, resulting in a lot of duplicate work.
- **6)**
The max time it will be called is n. When fib top down is called, the function computes all fibonacci numbers from 0 to n. so, the work and the span is O(n).
- **8)**
The max time it will be called is n. When fib bottom up is called, the function reads values from fibs[0] to fibs[n]. so, the work and the span is O(n).
