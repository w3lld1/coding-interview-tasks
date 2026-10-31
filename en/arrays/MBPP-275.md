# Position of the last removed element

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-275?utm_source=github&utm_medium=tasks-repo)**

Given a list of positive integers `numbers` and a positive integer `m`. The elements stand in a queue. At each step `m` is subtracted from the first element: if it becomes zero or less, it is removed; otherwise it goes to the end of the queue with its new value. Return the position (from 1) in the original list of the element that is removed last.

Clarification: an element `a` is removed in round `ceil(a / m)`, and among elements removed in the same round the one standing further right goes later. The list is not empty.

Example: `[2, 5, 4]`, `2` → `2` (rounds 1, 3, 2: the second element is removed last).

---

Source: [MBPP, task 275](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
