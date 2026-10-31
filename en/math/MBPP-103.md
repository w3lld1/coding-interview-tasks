# Eulerian number A(n, m)

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/), [Recursion and backtracking](../recursion/), [Dynamic programming](../dp/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-103?utm_source=github&utm_medium=tasks-repo)**

The Eulerian number `A(n, m)` is the count of permutations of the numbers 1 to `n` with exactly `m` ascents (an adjacent pair where the right number is larger than the left). Compute `A(n, m)` for `n ≥ 1` and `m ≥ 0` using these rules: if `m ≥ n`, the result is `0`; if `m = 0`, the result is `1`; otherwise `A(n, m) = (n - m) · A(n - 1, m - 1) + (m + 1) · A(n - 1, m)`.

Example: `3`, `1` → `4`.

---

Source: [MBPP, task 103](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
