# Jumps to a point

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-617?utm_source=github&utm_medium=tasks-repo)**

Given two positive jump lengths `step_a`, `step_b` and an integer `d >= 0`, let `a` be the smaller length and `b` the larger. Return a number by this rule: if `d >= b`, then `(d + b - 1) / b` (ordinary division, the result may be fractional); otherwise if `d = 0`, then `0`; otherwise if `d = a`, then `1`; otherwise `2`. The result is compared within 1e-6.

Example: `3`, `4`, `11` → `3.5`.

---

Source: [MBPP, task 617](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
