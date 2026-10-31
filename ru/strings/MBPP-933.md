# Из CamelCase в snake_case

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-933?utm_source=github&utm_medium=tasks-repo)**

Дана строка из латинских букв и цифр в стиле CamelCase. Верните её в стиле snake_case: все буквы строчные, слова разделены символом `_`. Новое слово начинается с заглавной буквы, если перед ней стоит строчная буква или цифра, либо если перед ней стоит заглавная, а после неё строчная (так `HTTPServer` даёт `http_server`). Пустая строка даёт пустую.

Пример: `"GoogleAssistant"` → `"google_assistant"`.

---

Источник: [MBPP, задача 933](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
