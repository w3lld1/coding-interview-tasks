# Обмены, уравнивающие двоичные строки

**Сложность:** сложная · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-838?utm_source=github&utm_medium=tasks-repo)**

Даны две двоичные строки одинаковой длины из символов `0` и `1`. За один ход можно выбрать любую позицию `i` в первой строке и любую позицию `j` во второй и поменять местами `s1[i]` и `s2[j]`. Верните наименьшее число ходов, после которых строки станут равны, или `-1`, если это невозможно.

Пример: `"0011"`, `"1111"` → `1` (обмен `s1[0]` и `s2[1]` даёт две строки `"1011"`).

---

Источник: [MBPP, задача 838](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
