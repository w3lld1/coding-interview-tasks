# Distance from latitude and longitude

**Difficulty:** medium · **Languages:** any of Python, JavaScript, TypeScript, Java, Go · **Topics:** [Math](../math/)

**[▶ Solve online on CodeShare](https://code-share.online/practice/MBPP-180?utm_source=github&utm_medium=tasks-repo)**

You get the latitude and longitude of two points on a sphere: `lat1`, `lon1`, `lat2`, `lon2`. All four values are in radians, so do not convert them. Return the distance between the points in kilometres using the spherical law of cosines: `6371.01 * acos(sin(lat1) * sin(lat2) + cos(lat1) * cos(lat2) * cos(lon1 - lon2))`. The tests do not use identical points.

Example: `0`, `0`, `0.5`, `0` → `3185.505`.

---

Source: [MBPP, task 180](https://github.com/google-research/google-research/tree/3bbd8fbea969c2ebee2bcce61711b5cd32b5ec32/mbpp) · © Google Research · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) · statement rewritten
