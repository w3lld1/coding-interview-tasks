# Возрастающая подпоследовательность с k-м элементом

**Сложность:** сложная · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Динамическое программирование](../dp/), [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-306?utm_source=github&utm_medium=tasks-repo)**

Дан список положительных целых `numbers` и два индекса `index < k`. Рассмотрите строго возрастающие подпоследовательности, которые состоят из элементов позиций `0..index` (возможно, ни одного) и заканчиваются элементом `numbers[k]`. Верните наибольшую сумму такой подпоследовательности, считая и сам `numbers[k]`.

Пример: `[1, 101, 2, 3, 100, 4, 5]`, `index = 4`, `k = 6` → `11` (подпоследовательность `1, 2, 3, 5`).

---

Источник: [MBPP, задача 306](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
