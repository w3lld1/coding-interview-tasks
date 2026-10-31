# The recommendation chain upwards

**Difficulty:** hard · **Language:** SQL (SQLite) · **Topics:** [SQL: joins](../sql-join/), [Recursion and backtracking](../recursion/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/PGEX-601?utm_source=github&utm_medium=tasks-repo)**

Find the recommendation chain of the member with `memid = 16`: who recommended them (`recommendedby`), who recommended that member, and so on up to a member with no recommender. Output the columns `memid`, `firstname`, `surname` for each link of the chain (not member 16 themselves). Sort by `memid` in ascending order.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises, recursive/getupward.html](https://pgexercises.com/questions/recursive/getupward.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data, rows sorted in ascending order
