# Rank members by (rounded) hours used

**Difficulty:** hard · **Language:** SQL (SQLite) · **Topics:** [SQL: window functions](../sql-window/), [SQL: aggregation](../sql-aggregate/), [SQL: joins](../sql-join/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-21?utm_source=github&utm_medium=tasks-repo)**

For each member with bookings, including the guest, compute the hours booked: one slot equals 30 minutes. Round the hours to the nearest ten, rounding exact halves up (5 hours → 10, 15 → 20). Rank by rounded hours in descending order with `RANK` semantics: equal values get the same rank, and gaps remain after a tie, for example `1, 1, 3`, not `DENSE_RANK`. Output first name, surname, rounded hours and rank; sort by rank, surname, first name.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Rank members by (rounded) hours used](https://pgexercises.com/questions/aggregates/rankmembers.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
