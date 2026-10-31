# Minimum platforms for a station

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Searching and sorting](../search-sort/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-846?utm_source=github&utm_medium=tasks-repo)**

At a station, the `i`-th train arrives at time `arrivals[i]` and departs at time `departures[i]`, with `arrivals[i] ≤ departures[i]`. A train occupies a platform for that whole interval inclusive: if one train arrives at the moment another departs, they need different platforms. Return the smallest number of platforms that is enough for all trains. With no trains the answer is `0`.

Example: `[900, 940, 950, 1100, 1500, 1800]`, `[910, 1200, 1120, 1130, 1900, 2000]` → `3`.

---

Source: [MBPP, task 846](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
