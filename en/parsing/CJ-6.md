# Decision tree probability

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Parsing and validation](../parsing/), [Recursion and backtracking](../recursion/), [Trees and graphs](../trees-graphs/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CJ-6?utm_source=github&utm_medium=tasks-repo)**

A decision tree is given as a string in this grammar: `tree ::= (weight [feature tree tree])`. The weight is a real number from 0 to 1, a feature is a word of lowercase Latin letters, and the part in square brackets is optional: a leaf has only a weight, every other node has a feature and two subtrees. Any two tokens (a bracket, a weight, a feature) are separated by at least one space or line break, except right after `(` and right before `)`, where there may be no whitespace. Extra spaces and line breaks are allowed.

To find the probability that an animal is cute, start at the root with `p = 1`. At each node multiply `p` by the node's weight. If the node is a leaf, stop: `p` is the answer. Otherwise, if the animal has the node's feature, go into the first subtree, and if not, into the second.

Given the string `tree` and a list of animals, each animal being the list of its features, return the probability for every animal in the same order. An error up to `1e-6` is accepted. The tree has at most 1000 nodes.

Example: the tree `"(0.5 cool\n  ( 1.000)\n  (0.5 ))"` (three lines), animals `[["cool"], []]` → `[0.5, 0.25]`.

---

Source: [Coding Competitions Archive, codejam/2009/round_1b/decision_tree](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2009/round_1b/decision_tree) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · statement rewritten
