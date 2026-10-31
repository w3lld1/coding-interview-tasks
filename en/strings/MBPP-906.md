# Dates in a page URL

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Parsing and validation](../parsing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-906?utm_source=github&utm_medium=tasks-repo)**

Given a string `url`, find every fragment of the form `/YYYY/M/D/`: a slash, exactly four digits, a slash, one or two digits, a slash, one or two digits, a slash. Search from left to right; found fragments do not overlap. For each fragment return a list of three strings `[year, month, day]` exactly as written (with a leading zero where present). If there are no such fragments, return an empty list.

Example: `"https://site.com/2021/5/7/post/"` → `[["2021", "5", "7"]]`.

---

Source: [MBPP, task 906](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
