# Spreading rot

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Matrices and grids](../matrices/), [Trees and graphs](../trees-graphs/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CS-2?utm_source=github&utm_medium=tasks-repo)**

A storeroom is a table of numbers: `0` is an empty cell, `1` a fresh orange, `2` a rotten one. Every minute each fresh orange with a rotten neighbour above, below, left or right becomes rotten (all infections of a minute happen at the same time). Return the number of minutes after which no fresh orange remains. If there were no fresh oranges at the start, the answer is `0`; if some fresh orange can never rot, the answer is `-1`. The table has at most 50×50 cells; an empty table gives `0`.

Example: `[[2, 1, 1], [1, 1, 0], [0, 1, 1]]` → `4`.

---

Source: a CodeShare task
