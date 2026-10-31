# Smallest-first course order

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Trees and graphs](../trees-graphs/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CS-4?utm_source=github&utm_medium=tasks-repo)**

There are `num_courses` courses numbered `0` to `num_courses - 1` (`num_courses` ≥ 1). A pair `[a, b]` in `prerequisites` means course `b` must be taken before course `a`. Return an order in which all courses can be taken. If several orders work, return the lexicographically smallest one (compare lists at the first differing element). If no order exists because of a cycle, return an empty list. There are at most 1000 courses and 5000 pairs.

Example: `4`, `[[1, 0], [2, 0], [3, 1], [3, 2]]` → `[0, 1, 2, 3]`; `4`, `[[0, 3], [3, 2]]` → `[1, 2, 3, 0]`.

---

Source: a CodeShare task
