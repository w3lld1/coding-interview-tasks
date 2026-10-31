# Вложенные списки как подмножество

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-216?utm_source=github&utm_medium=tasks-repo)**

Даны два списка списков целых чисел: `outer` и `inner`. Верните `true`, если каждый из списков `inner` равен (с тем же порядком элементов) какому-нибудь списку из `outer`, иначе `false`. Повторы не учитываются: достаточно, чтобы каждый список из `inner` нашёлся в `outer` хотя бы раз. Пустой `inner` даёт `true`.

Пример: `[[2, 3, 1], [4, 5], [6, 8]]`, `[[4, 5], [6, 8]]` → `true`.

---

Источник: [MBPP, задача 216](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
