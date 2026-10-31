# Римская запись в число

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Словари и множества](../hashing/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-961?utm_source=github&utm_medium=tasks-repo)**

Дана непустая строка с корректной записью числа римскими цифрами: `I`=1, `V`=5, `X`=10, `L`=50, `C`=100, `D`=500, `M`=1000. Если символ стоит перед бо́льшим, его значение вычитается (`IV`=4, `IX`=9, `XC`=90), иначе прибавляется. Букв `M` может быть и больше трёх подряд. Верните записанное число.

Пример: `"MCMXCIV"` → `1994`.

---

Источник: [MBPP, задача 961](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
