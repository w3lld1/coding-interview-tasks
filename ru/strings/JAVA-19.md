# Короткая публикация без повреждения Unicode

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-19?utm_source=github&utm_medium=tasks-repo)**

Реализуйте метод `truncate(String input)` класса `MicroBlog`. Он возвращает первые пять кодовых точек Unicode строки; более короткую строку возвращает без изменений. Нельзя просто взять первые пять значений `char`: символ вне основной многоязычной плоскости (например, эмодзи) занимает суррогатную пару из двух `char`, и разрывать её нельзя. Считайте именно кодовые точки, а не видимые графемы.

---

Источник: [Exercism — Java — Micro Blog](https://exercism.org/tracks/java/exercises/micro-blog) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
