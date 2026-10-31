# Split a number into three parts

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Recursion and backtracking](../recursion/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-416?utm_source=github&utm_medium=tasks-repo)**

For an integer `n` (from 0 to 100000) define `f(n)`. You may keep the number as it is or split it into three parts `⌊n/2⌋`, `⌊n/3⌋` and `⌊n/4⌋` (division rounded down), and each part may be split again by the same rule. `f(n)` is the largest total you can get. That is, `f(0) = 0`, and for `n ≥ 1` the value `f(n)` is the larger of `n` and `f(⌊n/2⌋) + f(⌊n/3⌋) + f(⌊n/4⌋)`. Return `f(n)`.

Example: `12` → `13` (12 = 6 + 4 + 3, where 6 → 3 + 2 + 1 = 6, 4 → 2 + 1 + 1 = 4, 3 stays, so 6 + 4 + 3 = 13).

---

Source: [MBPP, task 416](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
