# Calculate a rolling average of total revenue

**Difficulty:** hard · **Language:** SQL (SQLite) · **Topics:** [SQL: window functions](../sql-window/), [Dates and time](../dates/), [SQL: aggregation](../sql-aggregate/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-24?utm_source=github&utm_medium=tasks-repo)**

For each day of August 2012, compute the average daily revenue over that day and the 14 preceding calendar days (a 15-day window). Count days without bookings as revenue 0, and use July data for the start of August. Output the date (`YYYY-MM-DD`) and the average in ascending order of date.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Calculate a rolling average of total revenue](https://pgexercises.com/questions/aggregates/rollingavg.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
