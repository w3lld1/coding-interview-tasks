# Find the total revenue of each facility

**Difficulty:** medium · **Language:** SQL (SQLite) · **Topics:** [SQL: aggregation](../sql-aggregate/), [SQL: joins](../sql-join/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-17?utm_source=github&utm_medium=tasks-repo)**

Compute facility revenue from bookings: slots × guestcost for the guest with memid = 0, otherwise slots × membercost. Output the facility name and revenue in ascending order of revenue.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Find the total revenue of each facility](https://pgexercises.com/questions/aggregates/facrev.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
