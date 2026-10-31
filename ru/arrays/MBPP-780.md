# Покомпонентные суммы пар

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-780?utm_source=github&utm_medium=tasks-repo)**

Дан список пар целых чисел, каждая пара — список из двух чисел. Для каждой пары позиций `i < j` сложите пары покомпонентно: первое число с первым, второе со вторым. Верните список полученных пар в порядке перебора: сначала `i = 0` со всеми `j`, затем `i = 1` и так далее. Если пар меньше двух, результат пуст.

Пример: `[[1, 2], [3, 4], [5, 6]]` → `[[4, 6], [6, 8], [8, 10]]`.

---

Источник: [MBPP, задача 780](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
