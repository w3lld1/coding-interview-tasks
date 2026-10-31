# Roller coaster income

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Math](../math/), [Hash maps and sets](../hashing/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CJ-8?utm_source=github&utm_medium=tasks-repo)**

A queue of groups is waiting for a roller coaster: `groups[i]` is the size of the `i`-th group. The car holds at most `capacity` people. Groups board in queue order from the front until the groups run out or the next group does not fit whole (groups cannot be split or skipped); then the car goes, even if it is not full. After a ride all its passengers rejoin the back of the queue in the same order. A group boards at most once per ride, even if all groups already fit.

The coaster runs `rides` times. Every passenger pays 1 per ride. Return the total income.

Limits: `1 ≤ rides ≤ 10^8`, `1 ≤ capacity ≤ 5·10^7`, `1 ≤ groups[i] ≤ min(capacity, 10^7)`, at most 300 groups.

Example: `4`, `6`, `[1, 4, 2, 1]` → `21` (the rides take the groups [1, 4], [2, 1, 1], [4, 2], [1, 1, 4]).

---

Source: [Coding Competitions Archive, codejam/2010/qualification_round/theme_park](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2010/qualification_round/theme_park) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · statement rewritten
