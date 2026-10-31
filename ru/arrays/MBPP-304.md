# Элемент после вращений отрезков

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/), [Поиск и сортировка](../search-sort/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-304?utm_source=github&utm_medium=tasks-repo)**

Дан список `numbers`, список отрезков `ranges` (каждый отрезок — пара `[left, right]` с включёнными границами) и число `rotations`. По очереди выполните первые `rotations` вращений: для отрезка `[left, right]` сдвиньте его элементы на одну позицию вправо, а последний элемент отрезка поставьте на место `left`. Верните элемент на позиции `index` в итоговом списке. Если `rotations` равно `0`, список не меняется.

Пример: `[1, 2, 3, 4, 5]`, `[[0, 2], [0, 3]]`, `2`, `1` → `3` (после первого вращения `[3, 1, 2, 4, 5]`, после второго `[4, 3, 1, 2, 5]`).

---

Источник: [MBPP, задача 304](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
