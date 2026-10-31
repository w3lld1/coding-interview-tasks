# List to a binary min-heap

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-854?utm_source=github&utm_medium=tasks-repo)**

Given an arbitrary list of integers, turn it into a binary min-heap stored in an array: the children of the element at index `i` sit at `2i + 1` and `2i + 2` and are not smaller than it. Build the heap bottom-up: go from the last element that has children back to the start and sift each one down, swapping it with the smaller child while it is larger than that child. Return the resulting array.

Example: `[4, 5, 6, 2]` → `[2, 4, 6, 5]`.

---

Source: [MBPP, task 854](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
