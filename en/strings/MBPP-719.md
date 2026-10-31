# Letter a followed by any number of bs

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Parsing and validation](../parsing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-719?utm_source=github&utm_medium=tasks-repo)**

Given a string `text`, check whether it contains a fragment "the letter `a` followed by zero or more letters `b`". Because the `b`s after `a` are optional, any lowercase `a` anywhere in the string matches. If there is such a fragment, return the string `"Found a match!"`, otherwise `"Not matched!"`. An uppercase `A` does not count, and an empty string does not match.

Example: `"abba"` → `"Found a match!"`; `"dc"` → `"Not matched!"`.

---

Source: [MBPP, task 719](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
