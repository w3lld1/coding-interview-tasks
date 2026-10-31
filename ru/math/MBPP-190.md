# Целые точки внутри квадрата

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-190?utm_source=github&utm_medium=tasks-repo)**

Даны координаты `x1`, `y1` и `x2`, `y2` двух противоположных углов фигуры со сторонами, параллельными осям. Верните число точек с целыми координатами строго внутри неё (не на границе), считая по формуле `(x2 - x1 - 1) * (y2 - y1 - 1)`. Формула применяется ко всем входам как есть, без проверок: например, для совпадающих углов `(1, 2, 1, 2)` результат равен `1`.

Пример: `1`, `1`, `4`, `4` → `4`.

---

Источник: [MBPP, задача 190](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
