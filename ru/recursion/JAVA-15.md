# Замкнутая цепочка домино

**Сложность:** сложная · **Язык:** Java · **Темы:** [Рекурсия и перебор](../recursion/), [Деревья и графы](../trees-graphs/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-15?utm_source=github&utm_medium=tasks-repo)**

Реализуйте метод `formChain(List<Domino> inputDominoes)` класса `Dominoes`. Он должен выстроить все костяшки в замкнутую цепочку и вернуть её списком `List<Domino>`. Правое число каждой костяшки должно совпадать с левым числом следующей, а правое число последней — с левым числом первой. Костяшку можно переворачивать (создайте новый `Domino` с переставленными числами). Каждая костяшка используется ровно один раз, одинаковые костяшки считаются разными. Для пустого входа верните пустой список. Если цепочку построить нельзя, бросьте `ChainNotFoundException`.

---

Источник: [Exercism — Java — Dominoes](https://exercism.org/tracks/java/exercises/dominoes) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
