# Расстояние по широте и долготе

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-180?utm_source=github&utm_medium=tasks-repo)**

Даны широта и долгота двух точек на сфере: `lat1`, `lon1`, `lat2`, `lon2`. Все четыре значения заданы в радианах, переводить их не нужно. Верните расстояние между точками в километрах по сферической теореме косинусов: `6371.01 * acos(sin(lat1) * sin(lat2) + cos(lat1) * cos(lat2) * cos(lon1 - lon2))`. Для совпадающих точек тесты ответ не проверяют.

Пример: `0`, `0`, `0.5`, `0` → `3185.505`.

---

Источник: [MBPP, задача 180](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
