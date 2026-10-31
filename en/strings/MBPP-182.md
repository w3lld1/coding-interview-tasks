# Classify characters

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Parsing and validation](../parsing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-182?utm_source=github&utm_medium=tasks-repo)**

You get a string. Return a list of four lists of one-character strings, each keeping the order of appearance in the input: 1) uppercase Latin letters `A-Z`; 2) lowercase Latin letters `a-z`; 3) digits `0-9`; 4) "special" characters from this set: comma, space, dot, `!` and `?`. Any other character (including `#` and non-Latin letters) is skipped. For an empty string the result is four empty lists.

Example: `"Hi, You 2!"` → `[["H", "Y"], ["i", "o", "u"], ["2"], [",", " ", " ", "!"]]`.

---

Source: [MBPP, task 182](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
