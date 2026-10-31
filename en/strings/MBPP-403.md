# URL validation

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Parsing and validation](../parsing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-403?utm_source=github&utm_medium=tasks-repo)**

An address is valid if it fits the whole pattern below. It starts with `http://` or `https://`. Then comes the host name: at least two labels separated by dots. Each label is made of Latin letters, digits and hyphens and is never empty, and the last label is 2 to 6 Latin letters. After the host there may be a path: a `/`, `?` or `#` character followed by any characters without whitespace. The path is optional. Return `true` for a valid address and `false` for everything else, including the empty string.

Example: `"https://www.google.com"` → `true`, while `"https:/www.gmail.com"` → `false`.

---

Source: [MBPP, task 403](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
