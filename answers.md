# CMPS 2200 Recitation 06
## Answers

**Name:** Caitlyn Gifford


Place all written answers from `recitation-07.md` here for easier grading.



- **2)** W(0) = 0, W(1) = 0, W(n) = W(n - 1) + W(n - 2) + O(1). The work grows exponentially.

- **3)** Since the recurssive calls are not done in parallel, S(n) = S(n - 1) + S(n - 2) + O(1). The span grows exponentially.

- **4)** 

[34, 55, 34, 21, 13, 8, 5, 3, 2, 1, 1]

177

The counts list follows the fibonacci sequence, but going reverse. 

- **6)** The maximum number of times that fib_top_down(i) will be called for any value i is once. This is because of memoization (compute it once and save the result for later use). Work is W(n) = O(n) and span is S(n) = O(n)

- **8)**  The maximum number of times that $F_i$ will be read for any value i is twice. This is because $F_i$ is used to compute the next two numbers $F_i+1$ and $F_i+2$. Work is W(n) = O(n) and span is S(n) = O(n)
