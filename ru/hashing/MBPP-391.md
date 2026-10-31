# Вложенные словари из трёх списков

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Словари и множества](../hashing/), [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-391?utm_source=github&utm_medium=tasks-repo)**

Даны три списка: внешние ключи, внутренние ключи и числа. Для каждой позиции `i` постройте словарь `{outer_keys[i]: {inner_keys[i]: values[i]}}`: внешний ключ ведёт к словарю из одной пары «внутренний ключ → число». Верните список таких словарей по порядку позиций. Если списки разной длины, обработайте только позиции, которые есть во всех трёх; для пустых списков верните пустой список.

Пример: `["a", "b"]`, `["x", "y"]`, `[1, 2]` → `[{"a": {"x": 1}}, {"b": {"y": 2}}]`.

---

Источник: [MBPP, задача 391](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
