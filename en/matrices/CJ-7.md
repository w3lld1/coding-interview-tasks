# Triangular matrix by row swaps

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Matrices and grids](../matrices/), [Arrays and lists](../arrays/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CJ-7?utm_source=github&utm_medium=tasks-repo)**

Given a square matrix of zeros and ones as a list of `n` strings, each of `n` characters `0` and `1`. One move swaps two adjacent rows. Make all ones lie on the main diagonal or below it: in row number `x` (counted from 1) there are no ones to the right of column `x`.

Return the minimum number of moves. The goal is guaranteed to be reachable. The matrix is at most 40 × 40.

Example: `["001", "100", "010"]` → `2`.

---

Source: [Coding Competitions Archive, codejam/2009/round_2/crazy_rows](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2009/round_2/crazy_rows) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · statement rewritten
