# Merge rows that share a first element

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Hash maps and sets](../hashing/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-417?utm_source=github&utm_medium=tasks-repo)**

You get a list of non-empty lists of strings. Merge the lists with the same first element: for each value of the first element produce one list that starts with this value and then holds, in order of appearance, all other elements of every list with that start. The results go in the order in which each first-element value first appeared. Repeats are kept. An empty input gives an empty result.

Example: `[["x", "y"], ["x", "z"], ["w", "t"]]` → `[["x", "y", "z"], ["w", "t"]]`.

---

Source: [MBPP, task 417](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
