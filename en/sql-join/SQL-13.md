# Produce a list of all members, along with their recommender, using no joins

**Difficulty:** medium · **Language:** SQL (SQLite) · **Topics:** [SQL: joins](../sql-join/), [SQL: filtering](../sql-filter/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-13?utm_source=github&utm_medium=tasks-repo)**

Output the full name of each member and the full name of the person who recommended them, if any. Do not use JOIN; exclude identical result rows and sort by the member's full name.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Produce a list of all members, along with their recommender, using no joins.](https://pgexercises.com/questions/joins/sub.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
