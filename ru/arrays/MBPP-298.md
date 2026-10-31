# Элементы вложенных списков из заданного списка

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/), [Словари и множества](../hashing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-298?utm_source=github&utm_medium=tasks-repo)**

Даны список `allowed` и список списков `groups` (все числа целые). Для каждого внутреннего списка из `groups` оставьте только те элементы, которые встречаются в `allowed`, сохранив порядок и повторы. Верните список результатов в том же порядке, что и `groups`; внутренние списки без подходящих элементов превращаются в пустые.

Пример: `[1, 2, 3]`, `[[3, 9], [4], [2, 1, 2]]` → `[[3], [], [2, 1, 2]]`.

---

Источник: [MBPP, задача 298](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
