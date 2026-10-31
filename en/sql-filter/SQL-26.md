# Work out the end time of bookings

**Difficulty:** medium · **Language:** SQL (SQLite) · **Topics:** [SQL: filtering](../sql-filter/), [Dates and time](../dates/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-26?utm_source=github&utm_medium=tasks-repo)**

Compute the end of a booking as starttime plus slots × 30 minutes, in the same text format. Return starttime and endtime of the ten latest bookings, sorted by endtime descending, then by starttime descending.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Work out the end time of bookings](https://pgexercises.com/questions/date/endtimes.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
