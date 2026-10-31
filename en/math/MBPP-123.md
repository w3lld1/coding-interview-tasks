# Sum of amicable numbers

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-123?utm_source=github&utm_medium=tasks-repo)**

Let `d(a)` be the sum of proper divisors of `a` (divisors smaller than `a` itself; for 1 it is 0). A number `a` is amicable if `d(a) = b`, `d(b) = a` and `a ≠ b`. Return the sum of all amicable numbers `a` from 1 to `limit` inclusive. The partner `b` may exceed `limit`; only the numbers `a` in the range are summed. Assume `limit ≥ 1`.

Example: `220` → `220` (`d(220) = 284`, `d(284) = 220`), `284` → `504`.

---

Source: [MBPP, task 123](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
