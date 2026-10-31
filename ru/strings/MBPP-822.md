# Допустимый пароль

**Сложность:** лёгкая · **Языки:** любой из Python, JavaScript, TypeScript, Java, Go · **Темы:** [Строки](../strings/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/MBPP-822?utm_source=github&utm_medium=tasks-repo)**

Пароль допустим, если выполнены все условия: его длина от 6 до 12 символов включительно; есть хотя бы одна строчная латинская буква `a`–`z`, одна заглавная `A`–`Z`, одна цифра и один из символов `$`, `#`, `@`; нет пробельных символов (пробела, табуляции, перевода строки). Верните `true` для допустимого пароля, иначе `false`.

Пример: `"Password@10"` → `true`, `"password@10"` → `false` (нет заглавной буквы).

---

Источник: [MBPP, задача 822](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · условие переведено и дополнено
