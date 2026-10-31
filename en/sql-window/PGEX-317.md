# The least booked facilities

**Difficulty:** medium · **Language:** SQL (SQLite) · **Topics:** [SQL: window functions](../sql-window/), [SQL: aggregation](../sql-aggregate/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/PGEX-317?utm_source=github&utm_medium=tasks-repo)**

Find the facilities with the smallest sum of booked slots over all time. If several facilities share the smallest sum, output all of them. Columns: `facid` and `total` (the sum of `slots`). Row order does not matter.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises, aggregates/fachours4.html](https://pgexercises.com/questions/aggregates/fachours4.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data, asks for the smallest sum instead of the largest
