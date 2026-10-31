# Пары в заданном порядке ключей

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/), [Словари и множества](../hashing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-936?utm_source=github&utm_medium=tasks-repo)**

Дан список пар `[ключ, значение]` с различными ключами и список ключей `order`. Каждый ключ из `order` есть среди ключей пар. Верните список пар, расположенных в порядке `order`: для каждого ключа из `order` по очереди возьмите его пару. Ключ может повторяться в `order`, тогда его пара повторится в результате столько же раз. Пустой `order` даёт пустой список.

Пример: `[[1, 9], [4, 3], [2, 10]]`, `[2, 1, 2]` → `[[2, 10], [1, 9], [2, 10]]`.

---

Источник: [MBPP, задача 936](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
