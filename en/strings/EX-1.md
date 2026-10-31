# Affine cipher

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Strings](../strings/), [Math](../math/), [Errors and exceptions](../errors/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/EX-1?utm_source=github&utm_medium=tasks-repo)**

Implement the affine cipher for the 26-letter Latin alphabet. You get a mode (`"encode"` or `"decode"`), a text and a key of two integers `a` and `b` (`a` ≥ 1, `b` ≥ 0). When encoding, a letter with index `x` (letter "a" has index 0, "z" has 25) becomes the letter with index `(a·x + b) mod 26`; when decoding, a letter with index `y` becomes the letter with index `a⁻¹·(y − b) mod 26`, where `a⁻¹` is the number with `a·a⁻¹ mod 26 = 1`.

Letter case does not matter and the result is lowercase. Digits are kept unchanged and all other characters (spaces, punctuation) are dropped. When encoding, the result is split into groups of 5 characters separated by a space (the last group may be shorter); when decoding, the result has no spaces. If `a` and 26 are not coprime, report an error: throw an exception, or return an error in Go.

Example: `"encode"`, `"yes"`, `5`, `7` → `"xbt"`.

---

Source: [Exercism, affine-cipher](https://github.com/exercism/problem-specifications/tree/650bebeb39ad40439175288042aece982b0a90a9/exercises/affine-cipher) · © Exercism · [MIT](https://github.com/exercism/problem-specifications/blob/650bebeb39ad40439175288042aece982b0a90a9/LICENSE) · statement rewritten
