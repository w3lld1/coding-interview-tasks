# Двусвязный список

**Сложность:** средняя · **Язык:** Java · **Темы:** [Стек, очередь, связные списки](../stacks-lists/), [Классы и ООП](../oop/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-07?utm_source=github&utm_medium=tasks-repo)**

Реализуйте двусвязный список `DoublyLinkedList<T>`: каждый узел `Element<T>` хранит значение и ссылки на предыдущий и следующий узлы. Методы:

- `push(T value)` — добавить в конец; `pop()` — снять и вернуть значение с конца;
- `unshift(T value)` — добавить в начало; `shift()` — снять и вернуть значение с начала.

Операции должны правильно работать, когда в списке один элемент и когда список стал пустым после удалений.

---

Источник: [Exercism — Java — Linked List](https://exercism.org/tracks/java/exercises/linked-list) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
