# Проверка адреса электронной почты

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-774?utm_source=github&utm_medium=tasks-repo)**

Проверьте строку по упрощённым правилам и верните `true`, если адрес допустим. Адрес состоит из локальной части, символа `@` и домена. Локальная часть: не меньше двух строчных латинских букв или цифр и не больше одного разделителя `.` или `_` между ними; разделитель не может стоять в начале или в конце. Домен: имя из латинских букв, цифр и `_`, затем точка, затем зона из 2–3 таких же символов. Любая другая строка — `false`.

Пример: `"my.ownsite@ourearth.org"` → `true`; `"ankitaoie326.com"` → `false`.

---

Источник: [MBPP, задача 774](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
