# Find the top three revenue generating facilities

**Difficulty:** hard · **Language:** SQL (SQLite) · **Topics:** [SQL: window functions](../sql-window/), [SQL: aggregation](../sql-aggregate/), [SQL: joins](../sql-join/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-22?utm_source=github&utm_medium=tasks-repo)**

Compute facility revenue taking the guest rate into account and assign a `RANK` in descending order of revenue. Output the name and rank for ranks of 3 or better, including ties; sort by rank and name.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Find the top three revenue generating facilities](https://pgexercises.com/questions/aggregates/facrev3.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
