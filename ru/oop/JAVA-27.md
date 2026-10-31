# Иерархия бойцов

**Сложность:** средняя · **Язык:** Java · **Темы:** [Классы и ООП](../oop/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-27?utm_source=github&utm_medium=tasks-repo)**

Создайте два наследника класса `Fighter`: `Warrior` (воин) и `Wizard` (маг). В каждом переопределите методы:

- `toString()` — возвращает `"Fighter is a Warrior"` или `"Fighter is a Wizard"`;
- `isVulnerable()` — уязвим ли боец;
- `getDamagePoints(Fighter fighter)` — сколько урона боец наносит противнику `fighter`.

Воин никогда не уязвим; он наносит 10 урона уязвимому противнику и 6 — неуязвимому. Маг уязвим, пока не вызван его метод `prepareSpell()`; он наносит 3 урона без подготовки и 12 после вызова `prepareSpell()`.

---

Источник: [Exercism — Java — Wizards and Warriors](https://exercism.org/tracks/java/exercises/wizards-and-warriors) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
