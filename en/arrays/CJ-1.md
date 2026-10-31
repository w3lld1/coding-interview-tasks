# Train timetable

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Searching and sorting](../search-sort/), [Dates and time](../dates/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/CJ-1?utm_source=github&utm_medium=tasks-repo)**

Trains run between stations A and B. The timetable is two lists of trips: from A to B and from B to A. A trip is a pair of strings `["HH:MM", "HH:MM"]`: the departure time and the arrival time on the same day (24-hour clock, departure earlier than arrival, trips in any order).

A train that has arrived needs `turnaround` minutes before it can leave that station again (with `turnaround = 0` it may leave in the very minute it arrives). Trains run only trips from the timetable, may run several trips in a day, and at the moment of every departure a ready train must already be standing at the station.

Return a list `[x, y]`: the minimum number of trains that must start the day at station A (`x`) and at station B (`y`) so that the whole timetable can be run. Empty trip lists give `[0, 0]`. Each list has at most 100 trips.

Example: `5`, `[["09:00", "12:00"], ["10:00", "13:00"], ["11:00", "12:30"]]`, `[["12:02", "15:00"], ["09:00", "10:30"]]` → `[2, 2]`.

---

Source: [Coding Competitions Archive, codejam/2008/qualification_round/train_timetable](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2008/qualification_round/train_timetable) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · statement rewritten
