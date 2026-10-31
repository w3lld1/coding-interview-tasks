# Distinct powers of prime factors

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-714?utm_source=github&utm_medium=tasks-repo)**

Given a positive integer `n`, factor it into primes: each prime `p` divides `n` exactly `e` times. For one prime `p` you may pick the powers `p`, `p²`, `p³`, … one by one while the sum of exponents `1 + 2 + … + k` does not exceed `e`. Count how many powers can be picked over all prime factors together. For `n = 1` the answer is `0`.

Example: `24` → `3` (24 = 2³ · 3: for 2, 1 + 2 = 3 ≤ 3, so `2` and `2²`; for 3, take `3`).

---

Source: [MBPP, task 714](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
