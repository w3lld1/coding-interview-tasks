# Параллельный подсчёт букв

**Сложность:** сложная · **Язык:** Java · **Темы:** [Асинхронность и потоки](../async/), [Словари и множества](../hashing/), [Строки](../strings/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-16?utm_source=github&utm_medium=tasks-repo)**

Реализуйте класс `ParallelLetterFrequency`. Конструктор `ParallelLetterFrequency(String[] texts)` получает массив текстов. Метод `countLetters()` возвращает `Map<Character, Integer>`: сколько раз каждая буква (в нижнем регистре) встречается во всех текстах вместе. Регистр не различайте. Цифры, пунктуацию и пробелы не считайте, а буквы любых алфавитов Unicode считайте. Обрабатывайте тексты параллельно; слияние частичных результатов должно быть потокобезопасным и давать тот же ответ, что и последовательный подсчёт.

---

Источник: [Exercism — Java — Parallel Letter Frequency](https://exercism.org/tracks/java/exercises/parallel-letter-frequency) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
