# Удаление строк, целиком состоящих из null

**Сложность:** лёгкая · **Язык:** Python · **Темы:** [Массивы и списки](../arrays/), [Функции и замыкания](../functions/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-920?utm_source=github&utm_medium=tasks-repo)**

Дан список строк, каждая строка — список, элементы которого целые числа или `null`. Верните новый список, из которого удалены все строки, где каждый элемент равен `null`. Пустая строка (без элементов) тоже удаляется. Остальные строки сохраняются в прежнем порядке без изменений.

Пример: `[[null, 2], [null, null], [3, 4], [null]]` → `[[null, 2], [3, 4]]`.

---

Источник: [MBPP, задача 920](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
