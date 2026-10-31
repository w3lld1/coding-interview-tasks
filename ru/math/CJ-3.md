# Множества чисел

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/), [Деревья и графы](../trees-graphs/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/CJ-3?utm_source=github&utm_medium=tasks-repo)**

Дан отрезок последовательных целых чисел от `a` до `b` включительно и число `p`. Сначала каждое число лежит в своём собственном множестве. Затем для каждой пары чисел отрезка: если у них есть общий простой делитель, не меньший `p`, множества этих двух чисел объединяются.

Верните, сколько различных множеств получится в конце.

Ограничения: `1 ≤ a ≤ b ≤ 10^12`, `b - a ≤ 10^5`, `2 ≤ p ≤ min(b, 10^9)`.

Пример: `10`, `20`, `5` → `9` (вместе оказываются только 10, 15 и 20, остальные числа остаются поодиночке).

---

Источник: [Coding Competitions Archive, codejam/2008/round_1b/number_sets](https://github.com/google/coding-competitions-archive/tree/87385db7dbd81b281225412b8ad496334536d016/codejam/2008/round_1b/number_sets) · © Google LLC · [Apache-2.0](https://github.com/google/coding-competitions-archive/blob/87385db7dbd81b281225412b8ad496334536d016/LICENSE) · условие переведено и дополнено
