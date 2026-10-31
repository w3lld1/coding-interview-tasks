# First n lucky numbers

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-907?utm_source=github&utm_medium=tasks-repo)**

Lucky numbers come from a sieve. List all odd positive numbers in order: 1, 3, 5, 7, 9, … Take the second number of the list (3) and strike out every third number of the list. Then take the second number of the remaining list (7) and strike out every seventh, and so on: at each step you take the next number in order that has not been used as a step yet and strike out the positions divisible by it in the current list. The numbers that remain are lucky. Given an integer `n` from 1 to 50, return the first `n` lucky numbers in increasing order.

Example: `5` → `[1, 3, 7, 9, 13]`.

---

Source: [MBPP, task 907](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
