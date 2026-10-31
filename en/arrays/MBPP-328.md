# Left shift with prefix appended

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-328?utm_source=github&utm_medium=tasks-repo)**

Given a list of numbers and two numbers `skip` and `extra`, each between 0 and the length of the list, drop the first `skip` elements and then append the first `extra` elements of the original list to the end (keeping their order). Return the resulting list. It is a left shift by `skip` positions whose tail receives `extra` elements from the start.

Example: `[1, 2, 3, 4, 5]`, `2`, `1` → `[3, 4, 5, 1]`.

---

Source: [MBPP, task 328](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
