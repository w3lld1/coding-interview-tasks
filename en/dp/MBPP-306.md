# Increasing subsequence through the k-th element

**Difficulty:** hard · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-306?utm_source=github&utm_medium=tasks-repo)**

Given a list of positive integers `numbers` and two indices `index < k`, consider strictly increasing subsequences made of elements at positions `0..index` (possibly none) that end with `numbers[k]`. Return the largest sum of such a subsequence, including `numbers[k]` itself.

Example: `[1, 101, 2, 3, 100, 4, 5]`, `index = 4`, `k = 6` → `11` (subsequence `1, 2, 3, 5`).

---

Source: [MBPP, task 306](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
