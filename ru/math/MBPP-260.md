# Число Ньюмана — Шэнкса — Вильямса

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/), [Динамическое программирование](../dp/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-260?utm_source=github&utm_medium=tasks-repo)**

Последовательность чисел Ньюмана — Шэнкса — Вильямса задана так: первый и второй члены (с номерами 0 и 1) равны 1, а каждый следующий равен удвоенному предыдущему плюс член перед ним: `s(n) = 2·s(n-1) + s(n-2)`. Дано `n` (от 0 до 30). Верните `s(n)`.

Пример: `5` → `41` (последовательность 1, 1, 3, 7, 17, 41, …).

---

Источник: [MBPP, задача 260](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
