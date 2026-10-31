# Is it a min-heap

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Trees and graphs](../trees-graphs/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-751?utm_source=github&utm_medium=tasks-repo)**

A list of integers is stored as a binary heap: the children of the element at index `i` are at indexes `2i + 1` and `2i + 2` (when those indexes exist). Return `true` if the list is a min-heap, that is, every element is not greater than its children, otherwise `false`. Equal values are allowed. An empty list and a one-element list are heaps.

Example: `[2, 3, 4, 5, 10, 15]` → `true`.

---

Source: [MBPP, task 751](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
