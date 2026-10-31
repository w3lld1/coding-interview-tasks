# Последовательность Ньюмена — Конвея

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Динамическое программирование](../dp/), [Рекурсия и перебор](../recursion/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-84?utm_source=github&utm_medium=tasks-repo)**

Последовательность Ньюмена — Конвея задана так: P(1) = 1, P(2) = 1, а для n > 2 значение P(n) = P(P(n − 1)) + P(n − P(n − 1)). Дано целое `n` ≥ 1. Верните P(n).

Пример: `10` → `6` (последовательность: 1, 1, 2, 2, 3, 4, 4, 4, 5, 6).

---

Источник: [MBPP, задача 84](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
