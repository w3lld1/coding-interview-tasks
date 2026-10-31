# Maximum sum of a split

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Recursion and backtracking](../recursion/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-392?utm_source=github&utm_medium=tasks-repo)**

The function `f` is defined as `f(0) = 0`, and for `n ≥ 1` the value `f(n)` is the larger of `n` and `f(n/2) + f(n/3) + f(n/4) + f(n/5)`, where the division is integer division (the remainder is dropped). Given `n` from 0 to 100000, return `f(n)`.

Example: `10` → `12` (`f(5) = 5`, `f(3) = 3`, `f(2) = 2`, `f(2) = 2`, the sum `12` is larger than `10`).

---

Source: [MBPP, task 392](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
