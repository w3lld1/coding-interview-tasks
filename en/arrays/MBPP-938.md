# Closest triple from three lists

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-938?utm_source=github&utm_medium=tasks-repo)**

Given three non-empty lists of integers `a`, `b` and `c`, each sorted in ascending order, pick one number from each list so that the difference between the largest and the smallest of the three is as small as possible. Return the picked numbers as `[from a, from b, from c]`. If several triples are equally good, return the lexicographically smallest one (compare the number from `a` first, then from `b`, then from `c`).

Example: `[1, 4, 10]`, `[2, 15, 20]`, `[10, 12]` → `[10, 15, 10]` (difference 5; the triple `[10, 15, 12]` also gives 5, but it is lexicographically larger).

---

Source: [MBPP, task 938](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
