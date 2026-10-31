# Book store discounts

**Difficulty:** hard · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Dynamic programming](../dp/), [Recursion and backtracking](../recursion/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/EX-2?utm_source=github&utm_medium=tasks-repo)**

A shop sells a series of five books numbered 1 to 5. One book costs 800 cents. A group of different books gets a discount on each book in it, depending on the group size: 2 different books — 5%, 3 — 10%, 4 — 20%, 5 — 25%. A group contains books with different numbers only (two copies of one book cannot share a group), and a group of one book has no discount.

You get a list of the numbers of the books bought (numbers may repeat). Split the books into groups so that the total price is the lowest, and return it in cents (an integer). For an empty list return `0`.

The greedy "take the biggest group first" is not always optimal: two groups of 4 books are cheaper than a group of 5 plus a group of 3.

Example: `[1, 1, 2, 2, 3, 3, 4, 5]` → `5120` (two groups of 4 books).

---

Source: [Exercism, book-store](https://github.com/exercism/problem-specifications/tree/650bebeb39ad40439175288042aece982b0a90a9/exercises/book-store) · © Exercism · [MIT](https://github.com/exercism/problem-specifications/blob/650bebeb39ad40439175288042aece982b0a90a9/LICENSE) · statement rewritten
