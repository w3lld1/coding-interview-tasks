# Кодирование серий символов

**Сложность:** лёгкая · **Язык:** Java · **Темы:** [Строки](../strings/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-03?utm_source=github&utm_medium=tasks-repo)**

Реализуйте два метода класса `RunLengthEncoding`:

- `encode(String data)` сжимает строку: каждая серия одинаковых символов подряд записывается как её длина и сам символ, например `"AABBBC"` → `"2A3BC"`. Для одиночного символа длина не пишется.
- `decode(String data)` восстанавливает исходную строку из сжатой.

Исходная строка содержит только латинские буквы обоих регистров и пробелы, поэтому цифры в сжатой строке всегда означают длину следующей серии. Длина может быть многозначной (`"12W"`). Пустая строка в обоих направлениях даёт пустую строку.

---

Источник: [Exercism — Java — Run-Length Encoding](https://exercism.org/tracks/java/exercises/run-length-encoding) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
