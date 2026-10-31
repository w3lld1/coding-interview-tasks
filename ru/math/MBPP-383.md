# Инверсия битов на позициях 0, 2, 4…

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-383?utm_source=github&utm_medium=tasks-repo)**

Дано целое число `n` от 0 до 2³⁰ − 1. Номера битов отсчитываются от младшего, начиная с нуля. Инвертируйте в `n` каждый бит на чётной позиции (0, 2, 4, …), если эта позиция не выше старшего единичного бита `n`. Остальные биты не меняйте. Для `0` результат `0`.

Пример: `10` (двоичное `1010`) → `15` (`1111`).

---

Источник: [MBPP, задача 383](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
