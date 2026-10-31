# Longest chain of pairs

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-601?utm_source=github&utm_medium=tasks-repo)**

Given a list of pairs `[a, b]`, a chain is a selection of pairs taken in their order in the list (pairs may be skipped) in which the first number of every next pair is strictly greater than the second number of the previous one. Return the largest possible chain length. For an empty list the answer is `0`. A pair may have `a > b`; the rule does not care.

Example: `[[5, 24], [15, 25], [27, 40], [50, 60]]` → `3` (the chain `[5, 24]`, `[27, 40]`, `[50, 60]`).

---

Source: [MBPP, task 601](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
