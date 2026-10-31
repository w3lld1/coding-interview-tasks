# Links between numbers

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Hash maps and sets](../hashing/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-561?utm_source=github&utm_medium=tasks-repo)**

Given a list of integer pairs `[a, b]`, return a map: the keys are all numbers that appear in the pairs at any position (written as strings, such as `"3"`), and the value is the list of all `b` from pairs where this number is first, in the order of the pairs. Repeated pairs give repeated values. A number that only appears second gets an empty list. For an empty list of pairs the result is empty.

Example: `[[5, 3], [3, 8]]` → `{"5": [3], "3": [8], "8": []}`.

---

Source: [MBPP, task 561](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
