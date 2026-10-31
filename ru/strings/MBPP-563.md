# Значения в кавычках

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-563?utm_source=github&utm_medium=tasks-repo)**

Дана строка (без переводов строки). Верните список фрагментов, заключённых в двойные кавычки `"`, в порядке слева направо. Первая кавычка открывает фрагмент, следующая за ней закрывает его, после чего поиск продолжается дальше. Пара подряд идущих кавычек даёт пустую строку. Последняя незакрытая кавычка игнорируется. Если кавычек нет, результат пуст.

Пример: `say "hi" and "bye"` → `["hi", "bye"]`.

---

Источник: [MBPP, задача 563](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
