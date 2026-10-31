# Проверка даты по григорианскому календарю

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Даты и время](../dates/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-910?utm_source=github&utm_medium=tasks-repo)**

Даны три целых числа: месяц, день и год. Верните `true`, если такая дата существует в григорианском календаре, и `false` иначе. Годы считаются от 1. Месяц должен быть от 1 до 12, день — от 1 до числа дней в этом месяце. Февраль в високосный год имеет 29 дней, иначе 28. Год високосный, если он делится на 4, кроме годов, которые делятся на 100 и не делятся на 400.

Пример: `2`, `29`, `2000` → `true`; `2`, `29`, `1900` → `false`.

---

Источник: [MBPP, задача 910](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
