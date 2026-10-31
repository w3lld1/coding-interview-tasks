# Квадратный корень методом Герона

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-246?utm_source=github&utm_medium=tasks-repo)**

Дано неотрицательное число `number`. Вычислите его квадратный корень вавилонским методом (методом Герона), не пользуясь встроенным извлечением корня. Возьмите начальное приближение `g = number / 2`. Затем повторяйте замену `g` на среднее `g` и `number / g`, пока изменение не станет ничтожно малым. Для нуля верните `0`. Результат сравнивается с точностью до `1e-6`.

Пример: `9` → `3.0`.

---

Источник: [MBPP, задача 246](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
