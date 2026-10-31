# Подстановка элементов в шаблон

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-390?utm_source=github&utm_medium=tasks-repo)**

Дан список строк и шаблон — строка, в которой маркер `{0}` обозначает место для подстановки. Для каждого элемента списка верните копию шаблона, где каждый маркер `{0}` заменён на этот элемент. Если маркера в шаблоне нет, элемент не влияет на результат. Порядок сохраняется, пустой список даёт пустой список.

Пример: `["1", "2"]`, `"temp{0}"` → `["temp1", "temp2"]`.

---

Источник: [MBPP, задача 390](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
