# Склейка списков по кругу

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-81?utm_source=github&utm_medium=tasks-repo)**

Даны два списка чисел: `first` и непустой `second`. Верните список пар `[a, b]`: для каждого элемента `a` списка `first` возьмите `b` из `second` с той же позиции, а если `second` короче, продолжайте брать его элементы с начала по кругу. Длина результата равна длине `first`. Если `first` пуст, верните пустой список.

Пример: `[7, 8, 4, 5]`, `[1, 5, 6]` → `[[7, 1], [8, 5], [4, 6], [5, 1]]`.

---

Источник: [MBPP, задача 81](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
