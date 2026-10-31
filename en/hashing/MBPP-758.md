# Counting identical sublists

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Hash maps and sets](../hashing/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-758?utm_source=github&utm_medium=tasks-repo)**

You get a list of lists of integers. Count how many times each inner list occurs. Return a map: the key is the elements of the inner list joined by commas without spaces (for example `"1,3"`; an empty list gives the key `""`), the value is the number of such lists. Two lists are equal only if all elements match in the same order.

Example: `[[1, 3], [5, 7], [1, 3], [9]]` → `{"1,3": 2, "5,7": 1, "9": 1}`.

---

Source: [MBPP, task 758](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
