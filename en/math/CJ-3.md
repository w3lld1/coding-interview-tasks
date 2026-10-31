# Number sets

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/), [Trees and graphs](../trees-graphs/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CJ-3?utm_source=github&utm_medium=tasks-repo)**

Given the consecutive integers from `a` to `b` inclusive and a number `p`. At first every number is in a set of its own. Then for every pair of numbers in the interval: if they share a prime factor that is at least `p`, the sets of the two numbers are merged.

Return how many different sets remain at the end.

Limits: `1 ≤ a ≤ b ≤ 10^12`, `b - a ≤ 10^5`, `2 ≤ p ≤ min(b, 10^9)`.

Example: `10`, `20`, `5` → `9` (only 10, 15 and 20 end up together; every other number stays alone).

---

Source: [Coding Competitions Archive, codejam/2008/round_1b/number_sets](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2008/round_1b/number_sets) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · statement rewritten
