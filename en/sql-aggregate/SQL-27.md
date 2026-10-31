# Work out the utilisation percentage for each facility by month

**Difficulty:** hard · **Language:** SQL (SQLite) · **Topics:** [SQL: aggregation](../sql-aggregate/), [Dates and time](../dates/), [SQL: joins](../sql-join/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-27?utm_source=github&utm_medium=tasks-repo)**

Compute the percentage of time booked for each facility–month pair that had bookings, rounded to one decimal place. The club is open daily from 08:00 to 20:30, i.e. 25 slots per day; the denominator counts every day of the calendar month, even days without bookings. Output the facility name, the month (for example, `2012-09-01`) and the percentage, sorted by facility name and month.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Work out the utilisation percentage for each facility by month](https://pgexercises.com/questions/date/utilisationpermonth.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
