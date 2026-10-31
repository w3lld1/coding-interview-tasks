# Element after segment rotations

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-304?utm_source=github&utm_medium=tasks-repo)**

Given a list `numbers`, a list of segments `ranges` (each segment is a pair `[left, right]`, both ends included) and a number `rotations`, perform the first `rotations` rotations in order: for a segment `[left, right]`, shift its elements one position to the right and put the last element of the segment at position `left`. Return the element at position `index` in the final list. If `rotations` is `0`, the list is unchanged.

Example: `[1, 2, 3, 4, 5]`, `[[0, 2], [0, 3]]`, `2`, `1` → `3` (after the first rotation `[3, 1, 2, 4, 5]`, after the second `[4, 3, 1, 2, 5]`).

---

Source: [MBPP, task 304](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
