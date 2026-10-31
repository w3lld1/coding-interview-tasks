# Слияние трёх словарей

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Словари и множества](../hashing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-87?utm_source=github&utm_medium=tasks-repo)**

Даны три словаря со строковыми ключами и значениями: `first`, `second`, `third`. Верните один словарь со всеми ключами из трёх. Если ключ есть в нескольких словарях, берите значение из самого раннего: `first` приоритетнее `second`, а тот приоритетнее `third`. Исходные словари менять не нужно.

Пример: `{"B": "Black"}`, `{"B": "Blue", "G": "Green"}`, `{"G": "Gray"}` → `{"B": "Black", "G": "Green"}`.

---

Источник: [MBPP, задача 87](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
