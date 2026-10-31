# Справочник международных телефонных кодов

**Сложность:** средняя · **Язык:** Java · **Темы:** [Словари и множества](../hashing/), [Классы и ООП](../oop/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-30?utm_source=github&utm_medium=tasks-repo)**

Реализуйте класс `DialingCodes` — справочник телефонных кодов `Map<Integer, String>` (код → страна). Методы:

- `getCodes()` — вернуть всю карту;
- `setDialingCode(Integer code, String country)` — записать пару; если код уже есть, заменить страну;
- `getCountry(Integer code)` — страна по коду;
- `addNewDialingCode(Integer code, String country)` — добавить пару, но только если в справочнике нет ни такого кода, ни такой страны; иначе ничего не менять;
- `findDialingCode(String country)` — код страны или `null`, если страны нет;
- `updateCountryDialingCode(Integer code, String country)` — заменить код уже известной страны: удалить старую запись и добавить новую; для неизвестной страны ничего не делать.

---

Источник: [Exercism — Java — International Calling Connoisseur](https://exercism.org/tracks/java/exercises/international-calling-connoisseur) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
