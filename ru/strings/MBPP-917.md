# Заглавная буква и строчные в конце строки

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-917?utm_source=github&utm_medium=tasks-repo)**

Дана строка `text`. Верните строку `"Found a match!"`, если она оканчивается заглавной латинской буквой (`A`–`Z`), за которой идут одна или несколько строчных латинских букв (`a`–`z`) до самого конца строки. Иначе верните `"Not matched!"`. Перед заглавной буквой может стоять что угодно, в том числе другие заглавные.

Пример: `"AaBbGg"` → `"Found a match!"` (конец `Gg`), `"aA"` → `"Not matched!"`.

---

Источник: [MBPP, задача 917](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
