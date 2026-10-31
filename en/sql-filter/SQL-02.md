# Basic string searches

**Difficulty:** easy · **Language:** SQL (SQLite) · **Topics:** [SQL: filtering](../sql-filter/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-02?utm_source=github&utm_medium=tasks-repo)**

Select all facilities whose name contains the substring `Tennis` in exactly that case. Return all columns of these facilities.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Basic string searches](https://pgexercises.com/questions/basic/where3.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
