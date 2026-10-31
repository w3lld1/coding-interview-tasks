# Binary tree height

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Trees and graphs](../trees-graphs/), [Recursion and backtracking](../recursion/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-927?utm_source=github&utm_medium=tasks-repo)**

A binary tree is given by two lists of equal length. Nodes are numbered from zero and node `0` is the root. `left[i]` and `right[i]` are the numbers of the left and right child of node `i`, or `-1` when there is no such child. Return the height of the tree: the number of nodes on the longest path from the root down to a leaf. For an empty tree (both lists empty) return `0`.

Example: `[1, 3, -1, -1, -1]`, `[2, 4, -1, -1, -1]` → `3` (the root, its left child 1 and that child's child 3).

---

Source: [MBPP, task 927](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
