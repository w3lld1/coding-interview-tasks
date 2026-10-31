# Remove matching pairs

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Strings](../strings/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-484?utm_source=github&utm_medium=tasks-repo)**

Given two lists of string pairs, return a list that keeps only the pairs of the first list that are absent from the second one. Pairs are compared as a whole and the order inside a pair matters: `["a", "b"]` and `["b", "a"]` are different, and so are strings that differ in case or spaces. The order and repeats of the first list are kept.

Example: `[["Hello", "dude"], ["How", "are"], ["you", "?"]]`, `[["Hello", "dude"], ["How", "are"]]` → `[["you", "?"]]`.

---

Source: [MBPP, task 484](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
