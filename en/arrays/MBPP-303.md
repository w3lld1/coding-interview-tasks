# All inversions are adjacent

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-303?utm_source=github&utm_medium=tasks-repo)**

An inversion is a pair of positions `i < j` with `numbers[i] > numbers[j]`. Call it adjacent when `j = i + 1`. Given a list of integers, return `true` if the number of all inversions equals the number of adjacent inversions, otherwise `false`. An empty list and a one-element list have no inversions, so the answer is `true`.

Example: `[1, 0, 2]` → `true` (one inversion, and it is adjacent); `[1, 2, 0]` → `false` (inversions `1,0` and `2,0`, only the second is adjacent).

---

Source: [MBPP, task 303](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
