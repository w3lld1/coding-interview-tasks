# Максимальная сумма разбиения числа

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Динамическое программирование](../dp/), [Рекурсия и перебор](../recursion/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-392?utm_source=github&utm_medium=tasks-repo)**

Функция `f` задана так: `f(0) = 0`, а при `n ≥ 1` значение `f(n)` равно большему из двух чисел: `n` и `f(n/2) + f(n/3) + f(n/4) + f(n/5)`, где деление целочисленное (с отбрасыванием остатка). Дано `n` от 0 до 100000. Верните `f(n)`.

Пример: `10` → `12` (`f(5) = 5`, `f(3) = 3`, `f(2) = 2`, `f(2) = 2`, сумма `12` больше `10`).

---

Источник: [MBPP, задача 392](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
