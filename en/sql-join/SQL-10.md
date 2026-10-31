# Produce a list of all members, along with their recommender

**Difficulty:** medium · **Language:** SQL (SQLite) · **Topics:** [SQL: joins](../sql-join/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/SQL-10?utm_source=github&utm_medium=tasks-repo)**

For each member, show their first name and surname, along with the first name and surname of the member who recommended them. Keep rows without a recommender, filling the corresponding fields with NULL; sort by the recommended member's surname and first name.

The tables and data are already in the starter code and are created afresh on every run (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — club facilities; `membercost` and `guestcost` are the price of one slot for a member and for a guest.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — members; `recommendedby` is the `memid` of who invited them, or `NULL`; `memid = 0` is a guest.
- `bookings(bookid, facid, memid, starttime, slots)` — bookings; one slot is 30 minutes; `starttime` is text such as `2012-09-14 09:00:00`.

---

Source: [PostgreSQL Exercises — Produce a list of all members, along with their recommender](https://pgexercises.com/questions/joins/self2.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · adapted: retold in English, ported to SQLite, CodeShare sample data
