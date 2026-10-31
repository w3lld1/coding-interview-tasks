# Nested list elements found in a list

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Hash maps and sets](../hashing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-298?utm_source=github&utm_medium=tasks-repo)**

Given a list `allowed` and a list of lists `groups` (all numbers are integers). For each inner list of `groups`, keep only the elements that occur in `allowed`, preserving order and repeats. Return the list of results in the same order as `groups`; inner lists with no matching elements become empty.

Example: `[1, 2, 3]`, `[[3, 9], [4], [2, 1, 2]]` → `[[3], [], [2, 1, 2]]`.

---

Source: [MBPP, task 298](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
