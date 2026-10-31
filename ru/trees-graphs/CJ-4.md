# Булево дерево с подменой вентилей

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Деревья и графы](../trees-graphs/), [Динамическое программирование](../dp/), [Рекурсия и перебор](../recursion/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/CJ-4?utm_source=github&utm_medium=tasks-repo)**

Дано полное двоичное дерево логических вентилей. Узлы пронумерованы с 1, как в двоичной куче: у узла `x` дети `2x` и `2x + 1`. У каждого узла либо два ребёнка, либо ни одного. Внутренние узлы — это узлы `1 … len(gates)`, а листья — узлы с номерами `len(gates) + 1` и дальше.

`gates[i] = [g, c]` описывает внутренний узел `i + 1`: `g = 1` — вентиль AND, `g = 0` — OR; `c = 1` — вентиль можно заменить на противоположный (AND на OR или OR на AND), `c = 0` — нельзя. `leaves[i]` — значение листа с номером `len(gates) + 1 + i`. Значение внутреннего узла — AND или OR значений его детей.

Верните минимальное число замен вентилей, после которых в корне будет значение `v` (`0` или `1`). Если это невозможно, верните `-1`. Список `gates` не пуст, а листьев на один больше, чем вентилей.

Пример: `v = 1`, `gates = [[1, 0], [1, 1], [1, 1], [0, 0]]`, `leaves = [1, 0, 1, 0, 1]` → `1` (заменить вентиль узла 3 на OR).

---

Источник: [Coding Competitions Archive, codejam/2008/round_2/cheating_a_boolean_tree](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2008/round_2/cheating_a_boolean_tree) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · условие переведено и дополнено
