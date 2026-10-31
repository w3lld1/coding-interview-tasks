# Исключения в целочисленном калькуляторе

**Сложность:** средняя · **Язык:** Java · **Темы:** [Исключения](../errors/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-25?utm_source=github&utm_medium=tasks-repo)**

Реализуйте метод `calculate(int operand1, int operand2, String operation)` класса `CalculatorConundrum`. Операция — строка `"+"`, `"*"` или `"/"`. Метод возвращает строку вида `"a операция b = результат"`, например `calculate(22, 25, "+")` → `"22 + 25 = 47"`. Деление целочисленное. Ошибки:

- операция `null` или пустая строка — бросьте `IllegalArgumentException`;
- другая операция — бросьте `IllegalOperationException`;
- деление на ноль — перехватите `ArithmeticException` и бросьте `IllegalOperationException`, передав исходное исключение как причину (`cause`).

---

Источник: [Exercism — Java — Calculator Conundrum](https://exercism.org/tracks/java/exercises/calculator-conundrum) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
