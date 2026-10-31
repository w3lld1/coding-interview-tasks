# Двоичное дерево поиска

**Сложность:** средняя · **Язык:** Java · **Темы:** [Деревья и графы](../trees-graphs/), [Рекурсия и перебор](../recursion/), [Классы и ООП](../oop/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-06?utm_source=github&utm_medium=tasks-repo)**

Реализуйте обобщённое двоичное дерево поиска `BinarySearchTree<T extends Comparable<T>>`. Метод `insert(T value)` вставляет значение: если оно меньше или равно значению узла, спускайтесь в левое поддерево, если больше — в правое. Сравнивайте через `compareTo`. Другие методы:

- `getRoot()` возвращает корневой узел `Node<T>`; у узла есть методы `getData()`, `getLeft()` и `getRight()` (пустой ребёнок — `null`);
- `getAsSortedList()` возвращает все значения дерева по неубыванию, с повторами.

---

Источник: [Exercism — Java — Binary Search Tree](https://exercism.org/tracks/java/exercises/binary-search-tree) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
