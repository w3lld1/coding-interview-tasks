# Кольцевой буфер

**Сложность:** средняя · **Язык:** Java · **Темы:** [Стек, очередь, связные списки](../stacks-lists/), [Исключения](../errors/), [Классы и ООП](../oop/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-08?utm_source=github&utm_medium=tasks-repo)**

Реализуйте кольцевой буфер фиксированной вместимости — класс `CircularBuffer<T>`. Конструктор `CircularBuffer(int size)` задаёт вместимость. Методы:

- `write(T data)` — записать элемент; если буфер полон, бросьте `BufferIOException`;
- `read()` — вернуть и удалить самый старый элемент; если буфер пуст, бросьте `BufferIOException`;
- `overwrite(T data)` — записать элемент; если буфер полон, сначала удалить самый старый, иначе работает как `write`;
- `clear()` — удалить все элементы.

Элементы читаются в порядке записи.

---

Источник: [Exercism — Java — Circular Buffer](https://exercism.org/tracks/java/exercises/circular-buffer) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
