# Сумма чисел Перрина

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/), [Динамическое программирование](../dp/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-448?utm_source=github&utm_medium=tasks-repo)**

Числа Перрина задаются так: `P(0) = 3`, `P(1) = 0`, `P(2) = 2`, а дальше `P(k) = P(k-2) + P(k-3)` (3, 0, 2, 3, 2, 5, 5, 7, 10, 12, …). Дано целое `n ≥ 0`. Верните сумму `P(0) + P(1) + … + P(n)`. Результат помещается в 64-битное целое.

Пример: `9` → `49` (3 + 0 + 2 + 3 + 2 + 5 + 5 + 7 + 10 + 12 — это сумма до `P(9)`, равная 49).

---

Источник: [MBPP, задача 448](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
