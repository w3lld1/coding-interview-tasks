# Depth of a nested object

**Difficulty:** easy · **Language:** Python · **Topics:** [Recursion and backtracking](../recursion/), [Hash maps and sets](../hashing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-301?utm_source=github&utm_medium=tasks-repo)**

You get a value that is either a JSON object (key → value pairs) or something else (a number, a string, a list). Return its nesting depth: a value that is not an object has depth `0`; an object has depth one more than the deepest of its values. An empty object has depth `1`. Lists are not entered: an object inside a list does not count.

Example: `{"a": 1, "b": {"c": {"d": {}}}}` → `4`.

---

Source: [MBPP, task 301](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
