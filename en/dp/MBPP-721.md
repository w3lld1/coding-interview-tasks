# Path with the largest average in a square grid

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Matrices and grids](../matrices/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-721?utm_source=github&utm_medium=tasks-repo)**

Given a square `N × N` grid of integers (a list of rows), where each cell has a cost. A path starts at the top-left cell, moves only right or down at each step and ends at the bottom-right cell. The average of a path is the sum of the costs of the visited cells divided by their count. Return the largest average among all possible paths.

Example: `[[1, 2], [3, 4]]` → `2.6666666666666665` (the path 1 → 3 → 4 gives 8 / 3).

---

Source: [MBPP, task 721](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
