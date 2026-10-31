# Comb sort

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-71?utm_source=github&utm_medium=tasks-repo)**

Given a list of integers (negatives and duplicates allowed), return a new list with the same numbers in ascending order. Implement comb sort: start with a gap equal to the list length, before each pass divide the gap by 1.3 and drop the fractional part (never below 1), and compare elements that are `gap` apart, swapping those that are out of order. Stop when the gap is 1 and a pass made no swaps. An empty list or a list of one number is returned unchanged.

Example: `[5, 15, 37, 25, 79]` → `[5, 15, 25, 37, 79]`.

---

Source: [MBPP, task 71](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
