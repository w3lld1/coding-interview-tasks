# Set the bits at odd positions

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-48?utm_source=github&utm_medium=tasks-repo)**

Given an integer `n` from 0 to 10^9. Bit positions are numbered from one, starting at the lowest bit: 1, 2, 3, … Set to one every bit at an odd position (1, 3, 5, …) that is not above the highest set bit of `n`, and return the resulting number. The other bits stay unchanged. For `0` the answer is `0`.

Example: `10` → `15` (1010 → 1111).

---

Source: [MBPP, task 48](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
