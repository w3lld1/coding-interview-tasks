# Нижнетреугольная матрица перестановкой строк

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Матрицы и сетки](../matrices/), [Массивы и списки](../arrays/), [Поиск и сортировка](../search-sort/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/CJ-7?utm_source=github&utm_medium=tasks-repo)**

Дана квадратная матрица из нулей и единиц: список из `n` строк, каждая — строка из `n` символов `0` и `1`. За один ход можно поменять местами две соседние строки. Нужно добиться, чтобы все единицы лежали на главной диагонали или под ней: в строке номер `x` (с 1) справа от столбца `x` единиц нет.

Верните минимальное число ходов. Гарантируется, что цель достижима. Размер матрицы не больше 40 × 40.

Пример: `["001", "100", "010"]` → `2`.

---

Источник: [Coding Competitions Archive, codejam/2009/round_2/crazy_rows](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2009/round_2/crazy_rows) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · условие переведено и дополнено
