# Entringer number

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-346?utm_source=github&utm_medium=tasks-repo)**

The Entringer number E(n, k) for 0 ≤ k ≤ n is defined by: E(0, 0) = 1; E(n, 0) = 0 for n > 0; E(n, k) = E(n, k − 1) + E(n − 1, n − k) for k ≥ 1. Return E(n, k). The values are small: n does not exceed 15.

Example: `4`, `3` → `5`.

---

Source: [MBPP, task 346](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
