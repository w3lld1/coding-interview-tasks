# Проверка адреса URL

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-403?utm_source=github&utm_medium=tasks-repo)**

Адрес считается корректным, если он целиком подходит под такой шаблон. Он начинается с `http://` или `https://`. Дальше идёт имя хоста: не меньше двух меток, разделённых точками. Каждая метка состоит из латинских букв, цифр и дефисов и не бывает пустой, а последняя метка — это от 2 до 6 латинских букв. После хоста может идти путь: символ `/`, `?` или `#` и затем любые символы без пробелов. Путь необязателен. Верните `true` для корректного адреса и `false` для остальных, включая пустую строку.

Пример: `"https://www.google.com"` → `true`, а `"https:/www.gmail.com"` → `false`.

---

Источник: [MBPP, задача 403](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
