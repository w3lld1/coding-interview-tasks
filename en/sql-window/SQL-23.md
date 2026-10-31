# Classify facilities by value

**Difficulty:** hard · **Language:** SQL (SQLite) · **Topics:** [SQL: window functions](../sql-window/), [SQL: aggregation](../sql-aggregate/), [SQL: joins](../sql-join/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-23?utm_source=github&utm_medium=tasks-repo)**

Split the facilities by revenue into three groups as equal in row count as possible using `NTILE(3)` in descending order of revenue: groups 1, 2, 3 are labelled `high`, `average`, `low` respectively. Revenue is the total cost of bookings: slots × guestcost for the guest, slots × membercost for everyone else. Output the name and category; the order of categories is strictly `high → average → low` (group order, not alphabetical), and within a category, by name.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Classify facilities by value](https://pgexercises.com/questions/aggregates/classify.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
