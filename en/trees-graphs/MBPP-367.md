# Balanced tree

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Trees and graphs](../trees-graphs/), [Recursion and backtracking](../recursion/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-367?utm_source=github&utm_medium=tasks-repo)**

A binary tree is given by an array `tree` of positive node values: `tree[0]` is the root, and the children of the node at position `i` are at positions `2i + 1` (left) and `2i + 2` (right). The value `0` means "no node"; positions past the end of the array are empty too, and a missing node has no children. Return `true` if the tree is balanced: at every node the heights of the left and right subtrees differ by at most 1. An empty tree is balanced.

Example: `[1, 2, 3, 4, 5, 0, 0, 8]` → `false` (depth 3 on the left, 1 on the right).

---

Source: [MBPP, task 367](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
