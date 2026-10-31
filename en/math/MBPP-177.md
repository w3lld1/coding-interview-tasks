# Pair with LCM in range

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-177?utm_source=github&utm_medium=tasks-repo)**

You get the bounds `low` and `high` of a range (inclusive). The goal is two distinct numbers from the range whose LCM also lies in the range. If `2 * low <= high`, return the list `[low, 2 * low]`: both numbers are in the range and their LCM is `2 * low`. Otherwise no such pair exists and you return a list with one element, `[-1]`.

Example: `3`, `8` → `[3, 6]`; `5`, `9` → `[-1]`.

---

Source: [MBPP, task 177](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
