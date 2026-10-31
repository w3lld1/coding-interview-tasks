# Число Энтрингера

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Динамическое программирование](../dp/), [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-346?utm_source=github&utm_medium=tasks-repo)**

Число Энтрингера E(n, k), где 0 ≤ k ≤ n, задаётся так: E(0, 0) = 1; E(n, 0) = 0 при n > 0; E(n, k) = E(n, k − 1) + E(n − 1, n − k) при k ≥ 1. Верните E(n, k). Значения невелики: n не превосходит 15.

Пример: `4`, `3` → `5`.

---

Источник: [MBPP, задача 346](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
