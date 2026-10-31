# Эйлерово число A(n, m)

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/), [Рекурсия и перебор](../recursion/), [Динамическое программирование](../dp/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-103?utm_source=github&utm_medium=tasks-repo)**

Эйлерово число `A(n, m)` — количество перестановок чисел от 1 до `n`, в которых ровно `m` возрастаний (соседняя пара, где правое число больше левого). Вычислите `A(n, m)` для `n ≥ 1` и `m ≥ 0` по правилам: если `m ≥ n`, результат `0`; если `m = 0`, результат `1`; иначе `A(n, m) = (n - m) · A(n - 1, m - 1) + (m + 1) · A(n - 1, m)`.

Пример: `3`, `1` → `4`.

---

Источник: [MBPP, задача 103](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
