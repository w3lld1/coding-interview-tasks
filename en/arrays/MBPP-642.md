# Remove similar rows of a table

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Hash maps and sets](../hashing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-642?utm_source=github&utm_medium=tasks-repo)**

You are given a table as a list of rows, where each row is a list of integer pairs `[x, y]`. Two rows are similar if they consist of the same pairs, regardless of order and repeats. Return one representative of each group of similar rows: its pairs are sorted ascending (by `x`, then by `y`) with no repeats. The order of rows in the answer is arbitrary.

Example: `[[[4, 5], [3, 2]], [[2, 2], [4, 6]], [[3, 2], [4, 5]]]` → `[[[2, 2], [4, 6]], [[3, 2], [4, 5]]]`.

---

Source: [MBPP, task 642](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
