# Parity of the last element after p operations

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-134?utm_source=github&utm_medium=tasks-repo)**

Given a list of integers and a number `p ≥ 1`. One operation: take the sum of all elements of the list, add 1 and append the result to the end of the list. Perform the operation `p` times and return the string `"EVEN"` if the last element is even, or `"ODD"` if it is odd. The list may be empty (its sum is 0), and p may be large, so do not simulate the operations.

Example: `[5, 7, 10]`, `1` → `"ODD"` (the sum is 22, so 23 is appended).

---

Source: [MBPP, task 134](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
