# Square root by the Babylonian method

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-246?utm_source=github&utm_medium=tasks-repo)**

Given a non-negative number, compute its square root with the Babylonian (Heron's) method, without a built-in square root: start with the guess `x / 2` and keep replacing `g` with the average of `g` and `x / g` until the change is negligible. For zero return `0`. The result is compared within `1e-6`.

Example: `9` → `3.0`.

---

Source: [MBPP, task 246](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
