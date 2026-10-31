# Largest zero surplus in a substring

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Dynamic programming](../dp/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-125?utm_source=github&utm_medium=tasks-repo)**

Given a string `bits` of the characters `0` and `1`. For any substring (a contiguous piece of the string) the difference is the number of zeros minus the number of ones. Return the largest such difference over all non-empty substrings. If every substring has at least as many ones as zeros (or the string is empty), the result is `0`.

Example: `"11000010001"` → `6` (the substring `"00001000"` has seven zeros and one one).

---

Source: [MBPP, task 125](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
