# Ludic numbers

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-603?utm_source=github&utm_medium=tasks-repo)**

Ludic numbers come from a sieve. Take the list `1, 2, 3, …, n`. The number `1` is ludic. The next remaining number `k` is also ludic; then, among the remaining numbers after it, delete every `k`-th one (those at positions `k`, `2k`, `3k`, … after `k`). Repeat until the list is empty. Return all ludic numbers not greater than `n` in ascending order. If `n < 1`, return an empty list.

Example: `10` → `[1, 2, 3, 5, 7]`.

---

Source: [MBPP, task 603](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
