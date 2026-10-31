# Уровни журналирования через enum

**Сложность:** лёгкая · **Язык:** Java · **Темы:** [Разбор и проверка данных](../parsing/), [Классы и ООП](../oop/), [Строки](../strings/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-28?utm_source=github&utm_medium=tasks-repo)**

Строка журнала имеет вид `[КОД]: сообщение`. Заполните перечисление `LogLevel` и реализуйте класс `LogLine`:

- конструктор `LogLine(String logLine)` получает строку журнала;
- `getLogLevel()` возвращает уровень: код `TRC` — `TRACE`, `DBG` — `DEBUG`, `INF` — `INFO`, `WRN` — `WARNING`, `ERR` — `ERROR`, `FTL` — `FATAL`, любой другой код — `UNKNOWN`;
- `getOutputForShortLog()` возвращает краткую запись `"номер:сообщение"`, например `"[ERR]: Disk full"` → `"6:Disk full"`.

Номера уровней: `UNKNOWN` = 0, `TRACE` = 1, `DEBUG` = 2, `INFO` = 4, `WARNING` = 5, `ERROR` = 6, `FATAL` = 42.

---

Источник: [Exercism — Java — Logs, Logs, Logs!](https://exercism.org/tracks/java/exercises/logs-logs-logs) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
