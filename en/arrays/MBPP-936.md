# Pairs in a given key order

**Difficulty:** easy · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Hash maps and sets](../hashing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-936?utm_source=github&utm_medium=tasks-repo)**

Given a list of `[key, value]` pairs with distinct keys and a list of keys `order`, where every key of `order` appears among the pairs' keys, return the list of pairs arranged in the order of `order`: for each key of `order` in turn, take its pair. A key may repeat in `order`; then its pair repeats in the result as many times. An empty `order` gives an empty list.

Example: `[[1, 9], [4, 3], [2, 10]]`, `[2, 1, 2]` → `[[2, 10], [1, 9], [2, 10]]`.

---

Source: [MBPP, task 936](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
