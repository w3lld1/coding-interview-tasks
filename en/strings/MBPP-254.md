# Word tail from the first a or e

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Parsing and validation](../parsing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-254?utm_source=github&utm_medium=tasks-repo)**

Given a string of lowercase Latin letters and single spaces, where words are separated by spaces. For each word find its first letter `a` or `e`. If at least one more letter follows it in the word, add to the result the part of the word from that letter to the end of the word. If the word has no such letter, or the letter is the last one, the word adds nothing. Return the list of parts in word order. An empty string gives an empty list.

Example: `"python programe"` → `["ame"]` ("python" has no `a` or `e`; in "programe" the first `a` is followed by "me").

---

Source: [MBPP, task 254](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
