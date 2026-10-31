# Sum of Perrin numbers

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/), [Dynamic programming](../dp/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-448?utm_source=github&utm_medium=tasks-repo)**

The Perrin numbers are defined as `P(0) = 3`, `P(1) = 0`, `P(2) = 2`, and then `P(k) = P(k-2) + P(k-3)` (3, 0, 2, 3, 2, 5, 5, 7, 10, 12, …). Given an integer `n ≥ 0`, return the sum `P(0) + P(1) + … + P(n)`. The result fits into a 64-bit integer.

Example: `9` → `49` (3 + 0 + 2 + 3 + 2 + 5 + 5 + 7 + 10 + 12 is the sum up to `P(9)`, which equals 49).

---

Source: [MBPP, task 448](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
