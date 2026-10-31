# Newman-Conway sequence

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Recursion and backtracking](../recursion/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-84?utm_source=github&utm_medium=tasks-repo)**

The Newman-Conway sequence is defined by P(1) = 1, P(2) = 1, and for n > 2 by P(n) = P(P(n − 1)) + P(n − P(n − 1)). Given an integer `n` ≥ 1, return P(n).

Example: `10` → `6` (the sequence: 1, 1, 2, 2, 3, 4, 4, 4, 5, 6).

---

Source: [MBPP, task 84](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
