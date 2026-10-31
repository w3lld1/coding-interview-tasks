# Calculator Conundrum

**Difficulty:** medium · **Language:** Java · **Topics:** [Errors and exceptions](../errors/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/JAVA-25?utm_source=github&utm_medium=tasks-repo)**

Implement a calculator for two integer operands and a string operation symbol +, * or / that returns a string of the form "a operation b = result". For a null or empty operation symbol, throw IllegalArgumentException, and for an unsupported operation, throw IllegalOperationException. On division by zero, catch the ArithmeticException and wrap it in an IllegalOperationException, keeping the original exception as the cause; regular division is performed as integer division.

---

Source: [Exercism — Java — Calculator Conundrum](https://exercism.org/tracks/java/exercises/calculator-conundrum) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · statement retold in English
