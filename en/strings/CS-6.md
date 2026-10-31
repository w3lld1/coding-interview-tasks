# Word chain

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Trees and graphs](../trees-graphs/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CS-6?utm_source=github&utm_medium=tasks-repo)**

Given a start word `begin_word`, an end word `end_word` (they differ) and a list of allowed words `words`; all words use lowercase Latin letters and have the same length. One step replaces exactly one letter of the word so that the result is in `words`. The start word does not have to be in `words`. Return the number of words in the shortest chain from `begin_word` to `end_word`, counting both ends. If there is no chain (including when `end_word` is not in `words`), return `0`. `words` has at most 2000 words of length up to 10.

Example: `"hit"`, `"cog"`, `["hot", "dot", "dog", "lot", "log", "cog"]` → `5` (hit, hot, dot, dog, cog).

---

Source: a CodeShare task
