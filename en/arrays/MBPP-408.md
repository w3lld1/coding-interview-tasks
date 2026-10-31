# K pairs with the smallest sums

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-408?utm_source=github&utm_medium=tasks-repo)**

You get two lists of integers `nums1` and `nums2`, sorted ascending, and a number `k`. Consider all pairs `[x, y]` with `x` taken from the first list and `y` from the second. Return the `k` pairs with the smallest sums `x + y`, from the smaller sum to the larger. Pairs with equal sums go in the order of the position of `x` in the first list, and for equal positions in the order of the position of `y` in the second. If there are fewer than `k` pairs, return all of them; if `k = 0` or one list is empty, return an empty list.

Example: `[1, 3, 7]`, `[2, 4, 6]`, `2` → `[[1, 2], [1, 4]]`.

---

Source: [MBPP, task 408](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
