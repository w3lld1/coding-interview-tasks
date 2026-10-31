# Gold mine

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Matrices and grids](../matrices/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-423?utm_source=github&utm_medium=tasks-repo)**

You get a rectangular table of non-negative integers: the amount of gold in each cell of a mine. You choose any cell of the first column and then move right: to the cell on the right, right-up or right-down (when it exists). You collect the gold from all visited cells, including the first, and stop when you reach the last column. Return the largest amount of gold you can collect. For an empty table the answer is `0`.

Example: `[[10, 20], [30, 40]]` → `70` (30 from the bottom-left cell and 40 from the bottom-right one).

---

Source: [MBPP, task 423](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
