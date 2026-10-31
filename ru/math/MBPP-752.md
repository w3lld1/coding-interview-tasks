# Число Якобсталя

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/), [Динамическое программирование](../dp/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-752?utm_source=github&utm_medium=tasks-repo)**

Числа Якобсталя задаются так: `J(0) = 0`, `J(1) = 1`, а для остальных `n` значение `J(n) = J(n-1) + 2 * J(n-2)`. Дано `n` от `0` до `30`. Верните `J(n)`.

Пример: `5` → `11` (последовательность: `0, 1, 1, 3, 5, 11`).

---

Источник: [MBPP, задача 752](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
