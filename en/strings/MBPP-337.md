# Word at the end of a string

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Parsing and validation](../parsing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-337?utm_source=github&utm_medium=tasks-repo)**

Given a string with no line breaks, its last chunk is the part after the last space (the whole string if it has no spaces). Return `true` if the last chunk is not empty and contains at least one Latin letter, digit or `_`; punctuation may follow the word. If the string is empty, ends with a space, or its last chunk consists only of punctuation, return `false`.

Example: `"python."` → `true`; `"  lang  ."` → `false`.

---

Source: [MBPP, task 337](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
