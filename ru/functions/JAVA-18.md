# Базовые операции над списками

**Сложность:** средняя · **Язык:** Java · **Темы:** [Функции и замыкания](../functions/), [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-18?utm_source=github&utm_medium=tasks-repo)**

Реализуйте статические методы класса `ListOps` без готовых библиотечных аналогов:

- `append(list1, list2)` — новый список: элементы `list1`, затем `list2`;
- `concat(listOfLists)` — все списки подряд в одном списке (раскрывается только один уровень);
- `filter(list, predicate)` — элементы, для которых предикат истинен;
- `size(list)` — число элементов;
- `map(list, transform)` — результат функции для каждого элемента;
- `reverse(list)` — элементы в обратном порядке;
- `foldLeft(list, initial, f)` — свёртка слева направо: `acc = f(acc, x)`;
- `foldRight(list, initial, f)` — свёртка справа налево: `acc = f(x, acc)`.

Во всех операциях сохраняйте порядок элементов.

---

Источник: [Exercism — Java — List Ops](https://exercism.org/tracks/java/exercises/list-ops) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
