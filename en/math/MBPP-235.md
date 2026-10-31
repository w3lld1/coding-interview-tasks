# Set the even bits

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-235?utm_source=github&utm_medium=tasks-repo)**

Given a non-negative integer `n` (below `2^30`), number its bits from one, starting at the least significant bit. The highest bit of `n` is its leftmost one-bit. Set to one every bit with an even position (2, 4, 6, …) that is not above the highest bit of `n`, and return the resulting number. Odd positions and positions above the highest bit stay unchanged. For `0` the result is `0`.

Example: `20` → `30` (`10100` → `11110`).

---

Source: [MBPP, task 235](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
