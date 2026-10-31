# Минимум платформ на станции

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/), [Поиск и сортировка](../search-sort/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-846?utm_source=github&utm_medium=tasks-repo)**

У станции `i`-й поезд прибывает в момент `arrivals[i]` и отправляется в момент `departures[i]`, причём `arrivals[i] ≤ departures[i]`. Поезд занимает платформу весь этот промежуток включительно: если один поезд прибывает в тот же момент, когда другой отправляется, им нужны разные платформы. Верните наименьшее число платформ, достаточное для всех поездов. Без поездов ответ `0`.

Пример: `[900, 940, 950, 1100, 1500, 1800]`, `[910, 1200, 1120, 1130, 1900, 2000]` → `3`.

---

Источник: [MBPP, задача 846](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
