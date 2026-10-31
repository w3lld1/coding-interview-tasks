# Добавление во вложенный список

**Сложность:** лёгкая · **Язык:** Python · **Темы:** [Массивы и списки](../arrays/), [Функции и замыкания](../functions/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-307?utm_source=github&utm_medium=tasks-repo)**

Дан список `items` смешанных значений (числа, строки, `true`/`false`, `null`, списки), позиция `position` и число `value`. Элемент на позиции `position` — список. Верните копию `items`, в которой в конец этого вложенного списка добавлено `value`. Исходные данные менять нельзя: функция не должна изменять переданный список.

Пример: `["HELLO", 5, [], true]`, `2`, `50` → `["HELLO", 5, [50], true]`.

---

Источник: [MBPP, задача 307](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
