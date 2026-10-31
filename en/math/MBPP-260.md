# Newman-Shanks-Williams number

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/), [Dynamic programming](../dp/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-260?utm_source=github&utm_medium=tasks-repo)**

The Newman-Shanks-Williams sequence is defined like this: the first two terms (indices 0 and 1) are 1, and each next term is twice the previous one plus the term before it: `s(n) = 2·s(n-1) + s(n-2)`. Given `n` (0 to 30), return `s(n)`.

Example: `5` → `41` (the sequence is 1, 1, 3, 7, 17, 41, …).

---

Source: [MBPP, task 260](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
