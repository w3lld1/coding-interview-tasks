# Drainage basins

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Matrices and grids](../matrices/), [Trees and graphs](../trees-graphs/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CJ-5?utm_source=github&utm_medium=tasks-repo)**

Given an elevation map, a rectangular table `heights`. Water flows from each cell to at most one of its four neighbors (north, west, east, south; no diagonals).

- If no neighbor is strictly lower than the current cell, the water does not flow and the cell is a sink.
- Otherwise the water flows to the neighbor with the lowest height. On a tie it takes the first direction in this order: north, west, east, south.

All cells whose water ends up, directly or through other cells, in the same sink form one drainage basin. Label the basins with lowercase letters so that the string made by joining the rows of the map from top to bottom is lexicographically smallest: the basin of the top-left cell gets `a`, the next new basin met when scanning row by row from left to right gets `b`, and so on.

Return a list of strings shaped like the map: the basin letter of every cell. There are at most 26 basins and the map is at most 100 × 100.

Example: `[[9, 6, 3], [5, 9, 6], [3, 5, 9]]` → `["abb", "aab", "aaa"]`.

---

Source: [Coding Competitions Archive, codejam/2009/qualification_round/watersheds](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2009/qualification_round/watersheds) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · statement rewritten
