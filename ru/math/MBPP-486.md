# Биномиальная вероятность

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-486?utm_source=github&utm_medium=tasks-repo)**

Проводится `n` независимых испытаний, в каждом успех наступает с вероятностью `p`. Верните вероятность того, что успехов будет ровно `k`: `C(n, k) · pᵏ · (1 − p)ⁿ⁻ᵏ`, где `C(n, k)` — число сочетаний из `n` по `k`. Гарантируется `0 ≤ k ≤ n` и `0 ≤ p ≤ 1`. Ответ сравнивается с точностью `1e-6`.

Пример: `11`, `6`, `0.5` → `0.2255859375`.

---

Источник: [MBPP, задача 486](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
