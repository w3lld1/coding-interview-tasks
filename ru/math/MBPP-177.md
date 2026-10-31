# Пара чисел с НОК в диапазоне

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-177?utm_source=github&utm_medium=tasks-repo)**

Даны границы диапазона `low` и `high` (включительно). Нужно найти два различных числа из диапазона, НОК которых тоже лежит в диапазоне. Если `2 * low <= high`, верните список `[low, 2 * low]`: оба числа в диапазоне, а их НОК равен `2 * low`. Иначе такой пары нет, и нужно вернуть список из одного элемента `[-1]`.

Пример: `3`, `8` → `[3, 6]`; `5`, `9` → `[-1]`.

---

Источник: [MBPP, задача 177](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
