# Find the downward recommendation chain for member ID 1

**Difficulty:** hard · **Language:** SQL (SQLite) · **Topics:** [SQL: window functions](../sql-window/), [SQL: joins](../sql-join/), [Trees and graphs](../trees-graphs/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-30?utm_source=github&utm_medium=tasks-repo)**

Find all members recommended directly or indirectly by the member with memid = 1: the members they recommended, then the members those recommended, and so on. Output memid, first name and surname in memid order; do not include the original member in the result.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Find the downward recommendation chain for member ID 1](https://pgexercises.com/questions/recursive/getdownward.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
