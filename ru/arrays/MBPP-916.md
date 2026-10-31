# Значения тройки с заданной суммой

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Массивы и списки](../arrays/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-916?utm_source=github&utm_medium=tasks-repo)**

Даны список целых чисел `arr` и число `target`. Найдите три элемента на позициях `i < j < k`, сумма которых равна `target`. Если таких троек несколько, берётся та, у которой меньше `i`; при равных `i` — меньше `j`; при равных `i` и `j` — меньше `k`. Верните список из трёх значений `[arr[i], arr[j], arr[k]]` в порядке позиций. Если подходящей тройки нет (в том числе в списке меньше трёх элементов), верните пустой список.

Пример: `[1, 4, 45, 6, 10, 8]`, `22` → `[4, 10, 8]`.

---

Источник: [MBPP, задача 916](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
