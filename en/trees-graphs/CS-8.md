# Merging groups edge by edge

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Trees and graphs](../trees-graphs/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CS-8?utm_source=github&utm_medium=tasks-repo)**

There are `n` vertices numbered `0` to `n - 1` (`n` ≥ 1) with no links at first. Edges `[u, v]` are added one by one in the given order (no self-loops, repeats are possible). Return a list as long as the edge list whose `i`-th element is the number of connected components after the first `i + 1` edges are added. With no edges, return an empty list. There are at most 100000 vertices and 100000 edges.

Example: `4`, `[[0, 1], [2, 3], [1, 2]]` → `[3, 2, 1]`.

---

Source: a CodeShare task
