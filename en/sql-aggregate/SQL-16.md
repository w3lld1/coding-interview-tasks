# Popular club facilities

**Difficulty:** medium · **Language:** SQL (SQLite) · **Topics:** [SQL: aggregation](../sql-aggregate/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-16?utm_source=github&utm_medium=tasks-repo)**

Find the facilities whose total booked slots over all time are greater than 35. Output facid and the total, sorted by facid.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — List facilities with more than 1000 slots booked](https://pgexercises.com/questions/aggregates/fachours1a.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
