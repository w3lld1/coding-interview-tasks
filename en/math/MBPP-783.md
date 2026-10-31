# Convert an RGB colour to HSV

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-783?utm_source=github&utm_medium=tasks-repo)**

Given three integers from 0 to 255 — the red `r`, green `g` and blue `b` components — return a list of three numbers `[h, s, v]`: the hue in degrees from 0 (inclusive) to 360 (exclusive), and the saturation and value in percent from 0 to 100.

Divide the components by 255, let `mx` be the largest, `mn` the smallest and `d = mx - mn`. Value `v = mx * 100`. Saturation `s = 0` if `mx = 0`, otherwise `d / mx * 100`. Hue `h = 0` if `d = 0`. Otherwise, if `mx` is the red one: `60 * ((g - b) / d)`; the green one: `60 * ((b - r) / d) + 120`; the blue one: `60 * ((r - g) / d) + 240` (on ties check red first, then green). Bring the hue into the range 0 to 360 by adding 360 if it is negative. An error of 1e-6 is allowed.

Example: `255`, `0`, `0` → `[0.0, 100.0, 100.0]`.

---

Source: [MBPP, task 783](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
