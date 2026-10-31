# Generate a list of all the dates in October 2012

**Difficulty:** easy · **Language:** SQL (SQLite) · **Topics:** [SQL: window functions](../sql-window/), [Dates and time](../dates/), [Recursion and backtracking](../recursion/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-25?utm_source=github&utm_medium=tasks-repo)**

Produce all dates of October 2012 as text in the form `YYYY-MM-DD`, without querying the data tables.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Generate a list of all the dates in October 2012](https://pgexercises.com/questions/date/series.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
