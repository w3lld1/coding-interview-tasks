# Append to a nested list

**Difficulty:** easy · **Language:** Python · **Topics:** [Arrays and lists](../arrays/), [Functions and closures](../functions/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-307?utm_source=github&utm_medium=tasks-repo)**

Given a list `items` of mixed values (numbers, strings, `true`/`false`, `null`, lists), a position `position` and a number `value`, the element at `position` is a list. Return a copy of `items` where `value` is appended to the end of that nested list. Do not change the input: the function must not modify the list it receives.

Example: `["HELLO", 5, [], true]`, `2`, `50` → `["HELLO", 5, [50], true]`.

---

Source: [MBPP, task 307](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
