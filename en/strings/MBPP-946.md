# Most common characters of a text

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Hash maps and sets](../hashing/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-946?utm_source=github&utm_medium=tasks-repo)**

Given a string `text` and a number `k ≥ 0`, return a list of at most `k` of the most frequent characters of the string together with their counts. Each item is a string of the form `character:count`, for example `"s:4"`. Order: by count descending; characters with equal counts keep the order of their first appearance in the text. If there are fewer than `k` distinct characters, return all of them. For `k = 0` or an empty string return an empty list.

Example: `"abcab"`, `2` → `["a:2", "b:2"]`.

---

Source: [MBPP, task 946](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
