# Combinations with repetition

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Recursion and backtracking](../recursion/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-255?utm_source=github&utm_medium=tasks-repo)**

Given a list of distinct strings `items` and a number `n`, return all combinations of `n` elements with repetition: an element may be taken several times and the order inside a combination does not matter, so `["a", "b"]` and `["b", "a"]` are the same combination. Write each combination in the order in which its elements appear in `items`. The combinations themselves come in index order: first those starting with the first element, and so on, with the same rule inside. For `n = 0` the result is one empty list; for an empty `items` and `n > 0` the result is empty.

Example: `["a", "b"]`, `2` → `[["a", "a"], ["a", "b"], ["b", "b"]]`.

---

Source: [MBPP, task 255](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
