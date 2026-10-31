# Shell sort

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-428?utm_source=github&utm_medium=tasks-repo)**

Implement shell sort: return a new list with the same numbers in ascending order. Duplicates stay, and the input list must not be changed. An empty list and a list of one number are returned as they are.

Shell sort works like insertion sort, but it compares and moves elements by a step (a gap). The gap starts at half the list length and is halved each round until it reaches 1.

Example: `[24, 22, 39, 34, 87, 73, 68]` → `[22, 24, 34, 39, 68, 73, 87]`.

---

Source: [MBPP, task 428](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
