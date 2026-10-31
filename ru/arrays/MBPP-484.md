# Удаление совпадающих пар

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/), [Строки](../strings/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-484?utm_source=github&utm_medium=tasks-repo)**

Даны два списка пар строк. Верните список, в котором остались только пары первого списка, которых нет во втором. Пары сравниваются целиком и с учётом порядка: `["a", "b"]` и `["b", "a"]` разные, как и строки, отличающиеся регистром или пробелами. Порядок и повторы в первом списке сохраняются.

Пример: `[["Hello", "dude"], ["How", "are"], ["you", "?"]]`, `[["Hello", "dude"], ["How", "are"]]` → `[["you", "?"]]`.

---

Источник: [MBPP, задача 484](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
