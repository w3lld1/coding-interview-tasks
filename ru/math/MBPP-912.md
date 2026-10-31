# Число Лоба

**Сложность:** средняя · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Математика](../math/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-912?utm_source=github&utm_medium=tasks-repo)**

Число Лоба L(n, m) для целых `0 ≤ m ≤ n ≤ 15` равно (2m + 1) / (n + m + 1) · C(2n, n + m), где C(a, b) — биномиальный коэффициент (число способов выбрать `b` из `a`). Результат всегда целый. Верните L(n, m).

Пример: `4`, `2` → `20` (5/7 · C(8, 6) = 5/7 · 28).

---

Источник: [MBPP, задача 912](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
