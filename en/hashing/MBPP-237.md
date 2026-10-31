# Counting unordered pairs

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Hash maps and sets](../hashing/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-237?utm_source=github&utm_medium=tasks-repo)**

Given a list of pairs of integers (each pair is a list of two elements), treat `[a, b]` and `[b, a]` as the same pair. Return a list of triples `[smaller, larger, count]`, one for each distinct pair, where the count is how many times the pair occurs. Sort the triples by the smaller number, then by the larger one. For an empty list return an empty list.

Example: `[[3, 1], [1, 3], [6, 3]]` → `[[1, 3, 2], [3, 6, 1]]`.

---

Source: [MBPP, task 237](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
