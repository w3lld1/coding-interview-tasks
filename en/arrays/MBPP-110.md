# Gaps around intervals

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-110?utm_source=github&utm_medium=tasks-repo)**

Given a list of intervals (pairs `[a, b]`) and two numbers `start` and `stop`, process the intervals in order while keeping a current position `cur`; at first `cur = start`. For every interval `[a, b]` do two steps: (1) if `a > cur`, add the pair `[cur, a]` to the result and set `cur = b`; (2) then, if `cur < stop`, add the pair `[cur, stop]` to the result. Return the result. For an empty list of intervals the result is empty.

Example: `[[3, 4]]`, `1`, `10` → `[[1, 3], [4, 10]]`.

---

Source: [MBPP, task 110](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
