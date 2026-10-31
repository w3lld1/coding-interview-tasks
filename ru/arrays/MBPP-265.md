# Раздать элементы по кругу

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-265?utm_source=github&utm_medium=tasks-repo)**

Дан список строк `items` и целое `step` ≥ 1. Верните `step` списков: i-й содержит элементы `items` с индексами `i`, `i + step`, `i + 2·step`, … в исходном порядке (индексы с нуля). Если элементов не хватает, последние списки могут быть пустыми, но списков всегда ровно `step`.

Пример: `["a", "b", "c", "d", "e"]`, `2` → `[["a", "c", "e"], ["b", "d"]]`.

---

Источник: [MBPP, задача 265](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
