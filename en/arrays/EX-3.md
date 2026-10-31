# Bowling score

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Arrays and lists](../arrays/), [Errors and exceptions](../errors/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/EX-3?utm_source=github&utm_medium=tasks-repo)**

Compute the final score of one bowling game from the list of rolls. A game has 10 frames, and each frame starts with 10 pins standing. A frame has one or two rolls (the pins knocked down are an integer from 0 to 10):

- open frame: fewer than 10 pins fall in two rolls, the frame is worth the pins that fell;
- spare: all 10 pins fall in two rolls, the frame is worth 10 plus the pins of the next roll;
- strike: all 10 pins fall on the first roll (the frame has no second roll), the frame is worth 10 plus the pins of the next two rolls.

In the tenth frame a spare gives one extra roll and a strike gives two. Extra rolls only count towards the tenth frame and give no further rolls. After a strike in the tenth frame the two extra rolls can knock down more than 10 pins only if the first of them is a strike (otherwise their sum is at most 10). The result is the sum of the ten frames.

Report an error: throw an exception, or return an error in Go, if a roll is outside 0–10, a frame (other than a strike) has more than 10 pins, the game is not finished (rolls are missing, extra rolls included) or there are more rolls than the game needs.

Example: twenty rolls of `0` → `0`; `[10, 10, 10, 10, 10, 10, 10, 10, 10, 10, 10, 10]` → `300`.

---

Source: [Exercism, bowling](https://github.com/exercism/problem-specifications/tree/650bebeb39ad40439175288042aece982b0a90a9/exercises/bowling) · © Exercism · [MIT](https://github.com/exercism/problem-specifications/blob/650bebeb39ad40439175288042aece982b0a90a9/LICENSE) · statement rewritten
