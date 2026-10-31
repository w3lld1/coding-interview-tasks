# Собственное множество

**Сложность:** средняя · **Язык:** Java · **Темы:** [Классы и ООП](../oop/), [Словари и множества](../hashing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-09?utm_source=github&utm_medium=tasks-repo)**

Реализуйте обобщённое множество `CustomSet<T>` с конструкторами `CustomSet()` (пустое множество) и `CustomSet(Collection<T> data)`. Повторное добавление равного элемента не меняет множество, порядок элементов ни на что не влияет. Методы:

- `isEmpty()` — пусто ли множество;
- `contains(T element)` — есть ли элемент;
- `add(T element)` — добавить элемент;
- `isSubset(CustomSet<T> other)` — все элементы этого множества есть в `other`;
- `isDisjoint(CustomSet<T> other)` — нет общих элементов;
- `equals(Object obj)` — множества состоят из одних и тех же элементов;
- `getIntersection`, `getUnion`, `getDifference` (параметр `CustomSet<T> other`) — пересечение, объединение и разность; возвращают новый `CustomSet<T>`.

---

Источник: [Exercism — Java — Custom Set](https://exercism.org/tracks/java/exercises/custom-set) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
