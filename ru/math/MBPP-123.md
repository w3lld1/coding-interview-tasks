# Сумма дружественных чисел

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-123?utm_source=github&utm_medium=tasks-repo)**

Пусть `d(a)` — сумма собственных делителей числа `a` (делителей, меньших самого `a`; для 1 она равна 0). Число `a` называется дружественным, если `d(a) = b`, `d(b) = a` и `a ≠ b`. Верните сумму всех дружественных чисел `a` от 1 до `limit` включительно. Парное число `b` может быть больше `limit`; суммируются только сами `a` из диапазона. Считайте, что `limit ≥ 1`.

Пример: `220` → `220` (`d(220) = 284`, `d(284) = 220`), `284` → `504`.

---

Источник: [MBPP, задача 123](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
