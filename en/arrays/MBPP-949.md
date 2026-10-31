# Sort groups by total digits

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-949?utm_source=github&utm_medium=tasks-repo)**

Given a list of groups, each group a list of non-negative integers. For a group count the digits in the decimal notation of all its numbers together (the number `0` has one digit, an empty group has none). Return a new list of groups sorted by this count in ascending order. Groups with equal counts keep their original order. An empty list gives an empty list.

Example: `[[100], [1, 2], [45]]` → `[[1, 2], [45], [100]]` (2, 2 and 3 digits; equal groups keep their order).

---

Source: [MBPP, task 949](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
