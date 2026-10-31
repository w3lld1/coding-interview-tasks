# Потокобезопасный банковский счёт

**Сложность:** сложная · **Язык:** Java · **Темы:** [Асинхронность и потоки](../async/), [Исключения](../errors/), [Классы и ООП](../oop/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-17?utm_source=github&utm_medium=tasks-repo)**

Реализуйте класс банковского счёта `BankAccount` с методами `open()`, `close()`, `getBalance()`, `deposit(int amount)` и `withdraw(int amount)`. После открытия баланс равен нулю, в том числе когда закрытый счёт открывают снова. Бросайте `BankAccountActionInvalidException`, если:

- открывают уже открытый счёт;
- закрывают неоткрытый счёт;
- выполняют любую операцию с неоткрытым или закрытым счётом;
- сумма отрицательна;
- снимают больше, чем есть на счёте.

Пополнения и снятия могут идти одновременно из разных потоков: изменения не должны теряться, а ограничения — нарушаться.

---

Источник: [Exercism — Java — Bank Account](https://exercism.org/tracks/java/exercises/bank-account) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
