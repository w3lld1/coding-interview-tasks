# Планировщик записей в салон

**Сложность:** средняя · **Язык:** Java · **Темы:** [Даты и время](../dates/), [Разбор и проверка данных](../parsing/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-29?utm_source=github&utm_medium=tasks-repo)**

Реализуйте класс `AppointmentScheduler` с методами:

- `schedule(String appointmentDateDescription)` — разбирает строку формата `M/d/yyyy HH:mm:ss` (например, `"7/25/2019 13:45:00"`) и возвращает `LocalDateTime`;
- `hasPassed(LocalDateTime appointmentDate)` — `true`, если запись раньше текущего момента;
- `isAfternoonAppointment(LocalDateTime appointmentDate)` — `true`, если время записи от 12:00 включительно до 18:00 не включительно;
- `getDescription(LocalDateTime appointmentDate)` — строка по образцу `"You have an appointment on Friday, March 29, 2019, at 3:00 PM."`;
- `getAnniversaryDate()` — `LocalDate` годовщины открытия салона: 15 сентября текущего года.

---

Источник: [Exercism — Java — Booking Up For Beauty](https://exercism.org/tracks/java/exercises/booking-up-for-beauty) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
