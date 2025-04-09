# CMPS 2200 Recitation 06
## Answers

**Name:**______Joshua Burch___________________
**Name:**_________________________


Place all written answers from `recitation-07.md` here for easier grading.



- **2)**

W(n) = W(n-1) + W(n-2), W(0) = W(1) = 1

W(n) = O(2^n)

- **3)**

S(n) = max(S(n-1), S(n-2)) + O(1)

S(n) = S(n-1) + 1

S(n) = O(n)

- **4)**

It looks like a fibbonacci sequence

counts[i] = f(n-i)

- **6)**

The maximum number of calls for i is one, because after the first call the result is stored in fibs[i], so future calls just return the stored value

W(n) = O(n)

S(n) = O(n)


- **8)**

When computing $F_n$, what is the maximum number of times that $F_i$ will be read for any value is two times

W(n) = O(n) 

S(n) = O(n) 