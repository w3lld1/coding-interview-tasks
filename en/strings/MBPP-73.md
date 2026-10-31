# Split on several delimiters

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Parsing and validation](../parsing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-73?utm_source=github&utm_medium=tasks-repo)**

Split a string into parts at any of four delimiters: `"; "` (semicolon and space), `", "` (comma and space), `"*"` (asterisk) and a newline `"\n"`. Delimiters are not included in the result, and spaces outside delimiters are kept. A comma or semicolon without a following space is not a delimiter. Empty parts are kept: a string with no delimiter gives a list with one element (an empty string too).

Example: `"a, b*c"` → `["a", "b", "c"]`.

---

Source: [MBPP, task 73](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
