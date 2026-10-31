# Построение дерева из записей

**Сложность:** средняя · **Язык:** Java · **Темы:** [Деревья и графы](../trees-graphs/), [Исключения](../errors/), [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-23?utm_source=github&utm_medium=tasks-repo)**

В стартовом коде есть медленный метод `buildTree(ArrayList<Record> records)` класса `BuildTree`. Перепишите его так, чтобы он работал быстрее, но сохранил поведение. Метод получает записи `Record` в произвольном порядке; у каждой есть `getRecordId()` и `getParentId()`. Верните корень дерева `TreeNode`; дети каждого узла (`getChildren()`) должны идти по возрастанию `getNodeId()`. Для пустого списка верните `null`.

Правила корректности: для n записей идентификаторы образуют диапазон от 0 до n−1 без повторов; у корня `recordId` и `parentId` равны 0; у любого другого узла `parentId` меньше `recordId`. При нарушении бросьте `InvalidRecordsException`.

---

Источник: [Exercism — Java — Tree Building](https://exercism.org/tracks/java/exercises/tree-building) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
