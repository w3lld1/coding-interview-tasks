# Nested maps from three lists

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Hash maps and sets](../hashing/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-391?utm_source=github&utm_medium=tasks-repo)**

Given three lists: outer keys, inner keys and numbers. For each position `i` build a map with one key: the outer key `i` leads to a map with one key, where the inner key `i` leads to the number `i`. Return the list of such maps in the order of the positions. If the lists differ in length, process only the positions present in all three; for empty lists return an empty list.

Example: `["a", "b"]`, `["x", "y"]`, `[1, 2]` → `[{"a": {"x": 1}}, {"b": {"y": 2}}]`.

---

Source: [MBPP, task 391](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
