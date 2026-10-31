# Прыжки до точки

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-617?utm_source=github&utm_medium=tasks-repo)**

Даны две положительные длины прыжка `step_a`, `step_b` и целое `d >= 0`. Пусть `a` — меньшая из длин, `b` — большая. Верните число по такому правилу: если `d >= b`, то `(d + b - 1) / b` (обычное деление, результат может быть дробным); иначе если `d = 0`, то `0`; иначе если `d = a`, то `1`; иначе `2`. Результат сравнивается с точностью до 1e-6.

Пример: `3`, `4`, `11` → `3.5`.

---

Источник: [MBPP, задача 617](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
