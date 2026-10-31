# Binomial probability

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-486?utm_source=github&utm_medium=tasks-repo)**

`n` independent trials are made, and each succeeds with probability `p`. Return the probability of exactly `k` successes: `C(n, k) · pᵏ · (1 − p)ⁿ⁻ᵏ`, where `C(n, k)` is the number of combinations of `n` taken `k`. It is guaranteed that `0 ≤ k ≤ n` and `0 ≤ p ≤ 1`. The answer is compared with a tolerance of `1e-6`.

Example: `11`, `6`, `0.5` → `0.2255859375`.

---

Source: [MBPP, task 486](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
