# Work out the start times of bookings for tennis courts

**Difficulty:** easy · **Language:** SQL (SQLite) · **Topics:** [SQL: joins](../sql-join/), [Dates and time](../dates/), [SQL: filtering](../sql-filter/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-08?utm_source=github&utm_medium=tasks-repo)**

Output starttime and the court name for bookings on September 21, 2012, only for facilities named exactly `Tennis Court 1` and `Tennis Court 2`; `Table Tennis` is not included. Sort the rows by start time.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Work out the start times of bookings for tennis courts](https://pgexercises.com/questions/joins/simplejoin2.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
