# Число Каталана

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/), [Динамическое программирование](../dp/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-583?utm_source=github&utm_medium=tasks-repo)**

Верните `n`-е число Каталана, считая с нуля: 1, 1, 2, 5, 14, 42, … Они задаются так: `C(0) = 1`, а при `n ≥ 1` значение `C(n)` равно сумме `C(i) · C(n − 1 − i)` по `i` от 0 до `n − 1`. Гарантируется `0 ≤ n ≤ 15`.

Пример: `5` → `42`.

---

Источник: [MBPP, задача 583](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
