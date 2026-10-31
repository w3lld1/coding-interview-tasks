# Слово в конце строки

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-337?utm_source=github&utm_medium=tasks-repo)**

Дана строка без переводов строки. Последним фрагментом называется её конец после последнего пробела (если пробелов нет, вся строка). Верните `true`, если последний фрагмент не пуст и содержит хотя бы одну латинскую букву, цифру или символ `_`; за словом могут идти знаки препинания. Если строка пуста, заканчивается пробелом или последний фрагмент состоит только из знаков препинания, верните `false`.

Пример: `"python."` → `true`; `"  lang  ."` → `false`.

---

Источник: [MBPP, задача 337](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
