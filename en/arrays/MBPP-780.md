# Component-wise sums of pairs

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-780?utm_source=github&utm_medium=tasks-repo)**

Given a list of pairs of integers (each pair is a list of two numbers), take every pair of positions `i < j` and add the two pairs component-wise: first with first, second with second. Return the resulting pairs in iteration order: first `i = 0` with all `j`, then `i = 1`, and so on. With fewer than two pairs the result is empty.

Example: `[[1, 2], [3, 4], [5, 6]]` → `[[4, 6], [6, 8], [8, 10]]`.

---

Source: [MBPP, task 780](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
