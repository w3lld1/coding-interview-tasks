# Часы без календаря

**Сложность:** средняя · **Язык:** Java · **Темы:** [Классы и ООП](../oop/), [Математика](../math/), [Даты и время](../dates/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-20?utm_source=github&utm_medium=tasks-repo)**

Реализуйте класс часов `Clock`, которые хранят время суток без даты. Конструктор `Clock(int hours, int minutes)` принимает любые целые значения, в том числе отрицательные и больше 24 или 60, и приводит их к времени от 00:00 до 23:59 (например, `Clock(25, 0)` — это 01:00, а `Clock(-1, 0)` — 23:00). Методы:

- `add(int minutes)` — прибавляет минуты (отрицательное значение вычитает) с переходом через полночь;
- `toString()` — возвращает время в формате `HH:mm`, например `"08:05"`;
- `equals(Object obj)` — часы равны, если показывают одно и то же время.

---

Источник: [Exercism — Java — Clock](https://exercism.org/tracks/java/exercises/clock) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
