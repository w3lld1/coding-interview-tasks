# Boolean tree with swappable gates

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Trees and graphs](../trees-graphs/), [Dynamic programming](../dp/), [Recursion and backtracking](../recursion/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CJ-4?utm_source=github&utm_medium=tasks-repo)**

Given a complete binary tree of logic gates stored as a heap: node `x` has children `2x` and `2x + 1`, and every node has either two children or none. The interior nodes are `1 … len(gates)`; the leaves are the nodes numbered `len(gates) + 1` and up.

`gates[i] = [g, c]` describes interior node `i + 1`: `g = 1` means an AND gate, `g = 0` an OR gate; `c = 1` means the gate may be swapped for the opposite one (AND to OR or OR to AND), `c = 0` means it may not. `leaves[i]` is the value of leaf `len(gates) + 1 + i`. The value of an interior node is the AND or the OR of its children's values.

Return the minimum number of gate swaps after which the root has value `v` (`0` or `1`). If that is impossible, return `-1`. `gates` is never empty, and there is one more leaf than there are gates.

Example: `v = 1`, `gates = [[1, 0], [1, 1], [1, 1], [0, 0]]`, `leaves = [1, 0, 1, 0, 1]` → `1` (swap the gate of node 3 to OR).

---

Source: [Coding Competitions Archive, codejam/2008/round_2/cheating_a_boolean_tree](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2008/round_2/cheating_a_boolean_tree) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · statement rewritten
