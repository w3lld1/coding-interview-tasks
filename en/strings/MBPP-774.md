# Validate an email address

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Parsing and validation](../parsing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-774?utm_source=github&utm_medium=tasks-repo)**

Check a string against simplified rules and return `true` if the address is valid. An address is a local part, the character `@` and a domain. Local part: lowercase Latin letters and digits, at least two characters, with at most one separator `.` or `_` between them; the separator cannot be at the start or the end. Domain: a name of Latin letters, digits and `_`, then a dot, then a zone of 2-3 of the same characters. Any other string gives `false`.

Example: `"my.ownsite@ourearth.org"` → `true`; `"ankitaoie326.com"` → `false`.

---

Source: [MBPP, task 774](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
