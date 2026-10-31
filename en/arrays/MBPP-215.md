# Decode a run-length list

**Difficulty:** easy · **Language:** Python · **Topics:** [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-215?utm_source=github&utm_medium=tasks-repo)**

Given a list compressed by run lengths. Each of its elements is either a plain value (a number or a string) to be taken once, or a two-element list `[k, v]` where `k` ≥ 1 is an integer repeat count and `v` is the repeated value. The values `v` and the plain elements are never lists themselves. Return the expanded list. An empty list gives an empty list.

Example: `[[2, 1], 2, 3, [2, 4], 5, 1]` → `[1, 1, 2, 3, 4, 4, 5, 1]`.

---

Source: [MBPP, task 215](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
