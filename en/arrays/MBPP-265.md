# Deal items round-robin

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-265?utm_source=github&utm_medium=tasks-repo)**

Given a list of strings `items` and an integer `step` ≥ 1, return `step` lists: the i-th holds the elements of `items` at indices `i`, `i + step`, `i + 2·step`, … in the original order (zero-based). If there are too few elements, the last lists may be empty, but there are always exactly `step` lists.

Example: `["a", "b", "c", "d", "e"]`, `2` → `[["a", "c", "e"], ["b", "d"]]`.

---

Source: [MBPP, task 265](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
