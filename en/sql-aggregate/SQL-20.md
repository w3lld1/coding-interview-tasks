# List the total slots booked per facility per month, part 2

**Difficulty:** hard · **Language:** SQL (SQLite) · **Topics:** [SQL: aggregation](../sql-aggregate/), [Dates and time](../dates/), [SQL: filtering](../sql-filter/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-20?utm_source=github&utm_medium=tasks-repo)**

Compute the sum of slots per facility and month for 2012 (the month is a number from 1 to 12). Add a subtotal for each facility (month `NULL`) and a grand total for all facilities (facid and month `NULL`). Sort by facid and month so that each facility's subtotal comes after its months, and the grand total comes last.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — List the total slots booked per facility per month, part 2](https://pgexercises.com/questions/aggregates/fachoursbymonth3.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
