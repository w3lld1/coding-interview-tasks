# Цепочки приглашений для нескольких участников

**Сложность:** сложная · **Язык:** SQL (SQLite) · **Темы:** [SQL: JOIN](../sql-join/), [Рекурсия и перебор](../recursion/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/PGEX-603?utm_source=github&utm_medium=tasks-repo)**

Постройте CTE, который даёт цепочку приглашений вверх для любого участника, и с его помощью выведите цепочки участников 13 и 19. Столбцы: `member` (участник, чья цепочка), `recommender` (`memid` звена цепочки), `firstname` и `surname` этого звена. Отсортируйте по `member`, затем по `recommender`, оба по возрастанию.

Таблицы и данные уже есть в стартовом коде и создаются заново при каждом запуске (SQLite):

- `facilities(facid, name, membercost, guestcost, initialoutlay, monthlymaintenance)` — объекты клуба; `membercost` и `guestcost` — цена одного слота для участника и для гостя.
- `members(memid, surname, firstname, address, zipcode, telephone, recommendedby, joindate)` — участники; `recommendedby` — `memid` пригласившего или `NULL`; `memid = 0` — гость.
- `bookings(bookid, facid, memid, starttime, slots)` — бронирования; один слот — 30 минут; `starttime` — текст вида `2012-09-14 09:00:00`.

---

Источник: [PostgreSQL Exercises, recursive/getupwardall.html](https://pgexercises.com/questions/recursive/getupwardall.html) · © Alisdair Owens · [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) · адаптация: пересказ на русском, перенос на SQLite, учебные данные CodeShare, звенья сортируются по возрастанию
