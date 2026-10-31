# Values of a triplet with a given sum

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-916?utm_source=github&utm_medium=tasks-repo)**

Given a list of integers `arr` and a number `target`, look for three elements at positions `i < j < k` whose sum equals `target`. If there are several such triplets, take the one with the smaller `i`; for equal `i`, the smaller `j`; for equal `i` and `j`, the smaller `k`. Return a list of the three values `[arr[i], arr[j], arr[k]]` in the order of the positions. If there is no suitable triplet (including a list of fewer than three elements), return an empty list.

Example: `[1, 4, 45, 6, 10, 8]`, `22` → `[4, 10, 8]`.

---

Source: [MBPP, task 916](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
