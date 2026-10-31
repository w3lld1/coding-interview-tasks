# Hexagon grid

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/), [Arrays and lists](../arrays/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-493?utm_source=github&utm_medium=tasks-repo)**

Build a grid of regular pointy-top hexagons that covers the rectangle from `(start_x, start_y)` to `(end_x, end_y)`. Let `r` be the radius (`radius > 0`), `s = 2r / √3` the side, `p = s / 2`, `w = 2r`, `h = 2s`. Extend the area: `x₀ = start_x − w`, `y₀ = start_y − h`, `x_max = end_x + w`, `y_max = end_y + h`.

Rows go bottom to top: row number 1 is at `y = y₀` and each next row is `3p` higher while `y < y_max`. In odd rows the first hexagon is at `x = x₀`, in even rows at `x = x₀ + r`; the next one is always `w` to the right while `x < x_max`. A hexagon at point `(x, y)` is given by seven points `[x, y]` in this order: `(x, y+p)`, `(x, y+3p)`, `(x+r, y+h)`, `(x+w, y+3p)`, `(x+w, y+p)`, `(x+r, y)` and again `(x, y+p)`. Return the hexagons row by row, left to right. Coordinates are compared with a tolerance of `1e-6`.

Example: `0`, `0`, `0`, `0`, `1` → a list of 6 hexagons; the first one starts with the point `[-2, -1.7320508075688776]`.

---

Source: [MBPP, task 493](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
