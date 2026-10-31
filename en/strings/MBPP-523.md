# Password rule check

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Functions and closures](../functions/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-523?utm_source=github&utm_medium=tasks-repo)**

Given a string, check four rules in order: 1) it contains an uppercase Latin letter A–Z; 2) it contains a lowercase Latin letter a–z; 3) it contains a digit 0–9; 4) its length is at least 8. For each broken rule, add a message to the result: `String must have 1 upper case character.`, `String must have 1 lower case character.`, `String must have 1 number.`, `String length should be at least 8.` respectively. If nothing is broken, return a list with the single string `Valid string.`.

Example: `"123python"` → `["String must have 1 upper case character."]`.

---

Source: [MBPP, task 523](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
