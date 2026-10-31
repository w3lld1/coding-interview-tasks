# Промежутки вокруг интервалов

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-110?utm_source=github&utm_medium=tasks-repo)**

Даны список интервалов (пар `[a, b]`) и два числа `start` и `stop`. Обрабатывайте интервалы по порядку, храня текущую позицию `cur`; сначала `cur = start`. Для каждого интервала `[a, b]` сделайте два шага: (1) если `a > cur`, добавьте в результат пару `[cur, a]` и положите `cur = b`; (2) затем, если `cur < stop`, добавьте в результат пару `[cur, stop]`. Верните результат. Для пустого списка интервалов результат пуст.

Пример: `[[3, 4]]`, `1`, `10` → `[[1, 3], [4, 10]]`.

---

Источник: [MBPP, задача 110](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
