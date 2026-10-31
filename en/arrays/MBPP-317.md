# Run-length encoding with single items kept

**Difficulty:** medium · **Language:** Python · **Topics:** [Arrays and lists](../arrays/), [Strings](../strings/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-317?utm_source=github&utm_medium=tasks-repo)**

Given a list of values or a string, split it into runs of equal consecutive elements. Return a list in which a run of one element stays as the element itself, and a run of two or more is replaced by a pair `[length, element]`. If the input is a string, its elements are its characters (one-character strings). Empty input gives an empty list.

Example: `[1, 1, 2, 3, 4, 4, 5, 1]` → `[[2, 1], 2, 3, [2, 4], 5, 1]`.

---

Source: [MBPP, task 317](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
