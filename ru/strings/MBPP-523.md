# Проверка пароля по правилам

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Функции и замыкания](../functions/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-523?utm_source=github&utm_medium=tasks-repo)**

Дана строка. Проверьте четыре правила по порядку: 1) есть заглавная латинская буква A–Z; 2) есть строчная латинская буква a–z; 3) есть цифра 0–9; 4) длина не меньше 8. За каждое нарушенное правило добавьте в результат сообщение: `String must have 1 upper case character.`, `String must have 1 lower case character.`, `String must have 1 number.`, `String length should be at least 8.` соответственно. Если нарушений нет, верните список из одной строки `Valid string.`.

Пример: `"123python"` → `["String must have 1 upper case character."]`.

---

Источник: [MBPP, задача 523](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
