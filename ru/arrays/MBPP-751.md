# Проверка минимальной кучи

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/), [Деревья и графы](../trees-graphs/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-751?utm_source=github&utm_medium=tasks-repo)**

Список целых чисел записан как двоичная куча: потомки элемента с индексом `i` стоят на индексах `2i + 1` и `2i + 2` (если такие индексы есть в списке). Верните `true`, если список — min-куча, то есть каждый элемент не больше своих потомков, иначе `false`. Равные значения допустимы. Пустой список и список из одного элемента — куча.

Пример: `[2, 3, 4, 5, 10, 15]` → `true`.

---

Источник: [MBPP, задача 751](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
