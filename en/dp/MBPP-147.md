# Maximum path sum in a triangle

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-147?utm_source=github&utm_medium=tasks-repo)**

Given a triangle of numbers: the row with index `i` (from zero) holds `i + 1` integers. A path starts at the top and at each step goes down one row, either to the element directly below the current one (the same index `j`) or to its right neighbour (index `j + 1`). Return the largest possible sum of the numbers along a path from the top to the last row. The triangle is not empty.

Example: `[[1], [4, 8], [1, 5, 3]]` → `14` (path 1 → 8 → 5).

---

Source: [MBPP, task 147](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
