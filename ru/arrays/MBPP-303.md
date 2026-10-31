# Инверсии: все равны соседним

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/), [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-303?utm_source=github&utm_medium=tasks-repo)**

Инверсия — пара позиций `i < j`, где `numbers[i] > numbers[j]`. Назовём инверсию соседней, если `j = i + 1`. Дан список целых чисел. Верните `true`, если число всех инверсий равно числу соседних инверсий, иначе `false`. У пустого списка и списка из одного числа инверсий нет, ответ `true`.

Пример: `[1, 0, 2]` → `true` (одна инверсия, и она соседняя); `[1, 2, 0]` → `false` (инверсии `1,0` и `2,0`, соседняя только вторая).

---

Источник: [MBPP, задача 303](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
