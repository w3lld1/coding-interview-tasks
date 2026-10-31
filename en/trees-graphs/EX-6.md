# Hex game winner

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Trees and graphs](../trees-graphs/), [Matrices and grids](../matrices/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/EX-6?utm_source=github&utm_medium=tasks-repo)**

The game Hex is played on a rhombus board of hexagonal cells. The board is a list of rows of equal length: `X` is a stone of player X, `O` is a stone of player O, `.` is an empty cell. The board has at least one cell. On the picture each next row is shifted right by half a cell, so the cell `(r, c)` (row `r`, column `c`) touches six cells: `(r, c−1)`, `(r, c+1)`, `(r−1, c)`, `(r−1, c+1)`, `(r+1, c−1)` and `(r+1, c)` (when they are on the board).

Player `X` wins if a chain of touching X stones joins the left column to the right column. Player `O` wins if a chain of touching O stones joins the top row to the bottom row. Return `"X"`, `"O"`, or the empty string `""` if nobody has won. The board may be "unfair" (different stone counts, not a square). At most one player wins.

Example: `["XO", "OX"]` → `"O"` (the `O` stones in cells `(0, 1)` and `(1, 0)` touch and join the top row to the bottom row; the `X` stones do not).

---

Source: [Exercism, connect](https://github.com/exercism/problem-specifications/tree/650bebeb39ad40439175288042aece982b0a90a9/exercises/connect) · © Exercism · [MIT](https://github.com/exercism/problem-specifications/blob/650bebeb39ad40439175288042aece982b0a90a9/LICENSE) · statement rewritten
