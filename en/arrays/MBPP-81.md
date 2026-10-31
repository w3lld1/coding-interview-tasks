# Zip with wrap-around

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-81?utm_source=github&utm_medium=tasks-repo)**

Given two lists of numbers, `first` and a non-empty `second`, return a list of pairs `[a, b]`: for each element `a` of `first`, take `b` from `second` at the same position, and if `second` is shorter, keep taking its elements from the start in a cycle. The result has the length of `first`. If `first` is empty, return an empty list.

Example: `[7, 8, 4, 5]`, `[1, 5, 6]` → `[[7, 1], [8, 5], [4, 6], [5, 1]]`.

---

Source: [MBPP, task 81](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
