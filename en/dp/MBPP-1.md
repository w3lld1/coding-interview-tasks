# Minimum cost path in a grid

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Matrices and grids](../matrices/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-1?utm_source=github&utm_medium=tasks-repo)**

Given a grid of non-negative costs `cost` and a target cell (`row`, `col`), return the minimum total cost of a path from the top-left cell (0, 0) to the target cell. From cell (i, j) a step goes right, down, or diagonally down-right. The cost of a path is the sum of the costs of all its cells, including the first and the last. The grid may be larger than the part needed to reach the target.

Example: `[[1, 2, 3], [4, 8, 2], [1, 5, 3]]`, `2`, `2` → `8` (the path 1 → 2 → 2 → 3).

---

Source: [MBPP, task 1](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
