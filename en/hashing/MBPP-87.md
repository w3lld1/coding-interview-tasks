# Merge three maps

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Hash maps and sets](../hashing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-87?utm_source=github&utm_medium=tasks-repo)**

Given three maps with string keys and string values: `first`, `second`, `third`. Return one map with all keys from the three. If a key occurs in several maps, take the value from the earliest one: `first` wins over `second`, which wins over `third`. The input maps must not be changed.

Example: `{"B": "Black"}`, `{"B": "Blue", "G": "Green"}`, `{"G": "Gray"}` → `{"B": "Black", "G": "Green"}`.

---

Source: [MBPP, task 87](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
