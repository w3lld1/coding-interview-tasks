# Mini Forth evaluator

**Difficulty:** hard · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Parsing and validation](../parsing/), [Stacks, queues, linked lists](../stacks-lists/), [Errors and exceptions](../errors/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/EX-9?utm_source=github&utm_medium=tasks-repo)**

Implement an evaluator for a tiny Forth. You get a list of instruction strings; run them in order with one shared stack of integers and one shared dictionary of words. Return the final stack from bottom to top.

Tokens are separated by spaces and are case-insensitive (`DUP`, `Dup` and `dup` are the same word). A number is an optional `-` followed by one or more digits: it is pushed on the stack. Built-in words: `+`, `-`, `*`, `/` pop the top two values `a` (deeper) and `b` (on top) and push `a+b`, `a-b`, `a*b` and `a/b` (integer division, rounding toward zero); `dup` copies the top value; `drop` removes it; `swap` exchanges the top two values; `over` pushes a copy of the second value from the top.

A line of the form `: name body ;` defines a word; the body is the tokens between the name and the `;`. A definition captures the words of its body as they mean at the moment of definition, so a later redefinition does not affect words that already exist, and a word may use its own previous meaning (`: foo foo 1 + ;`). Built-in words and earlier user words can be redefined.

Report an error: throw an exception, or return an error in Go, when: the stack has too few values for a word, a divisor is zero, the name being defined is a number (`: 1 2 ;`), or an unknown word is met (also inside a definition body). An empty list of instructions gives an empty stack.

Example: `[": dup-twice dup dup ;", "1 dup-twice"]` → `[1, 1, 1]`.

---

Source: [Exercism, forth](https://github.com/exercism/problem-specifications/tree/650bebeb39ad40439175288042aece982b0a90a9/exercises/forth) · © Exercism · [MIT](https://github.com/exercism/problem-specifications/blob/650bebeb39ad40439175288042aece982b0a90a9/LICENSE) · statement rewritten
