# Milkshake batches

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Hash maps and sets](../hashing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CJ-2?utm_source=github&utm_medium=tasks-repo)**

A shop can make `n` milkshake flavors, and each flavor can be prepared plain (`0`) or malted (`1`). Exactly one batch is made per flavor: either plain or malted. Every customer has a list of liked types, pairs `[flavor, kind]` with flavors numbered from 1. A customer is satisfied if at least one of their types is prepared. A customer likes at most one malted type.

Satisfy all customers while making as few malted batches as possible. When all customers can be satisfied, such a set of batches is unique. Return a list of `n` numbers: `1` if the batch of flavor `i` is malted, `0` if plain. If the customers cannot all be satisfied, return an empty list. With no customers every batch is plain.

Limits: `1 ≤ n ≤ 2000`, at most 2000 customers, at most 3000 pairs in total.

Example: `5`, `[[[1, 1]], [[1, 0], [2, 0]], [[5, 0]]]` → `[1, 0, 0, 0, 0]`.

---

Source: [Coding Competitions Archive, codejam/2008/round_1a/milkshakes](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2008/round_1a/milkshakes) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · statement rewritten
