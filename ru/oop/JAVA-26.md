# Интерфейс машин и рейтинг побед

**Сложность:** средняя · **Язык:** Java · **Темы:** [Классы и ООП](../oop/), [Поиск и сортировка](../search-sort/)

**[▶ Решить онлайн на CodeShare](https://code-share.ru/practice/JAVA-26?utm_source=github&utm_medium=tasks-repo)**

Объявите интерфейс `RemoteControlCar` с методами `void drive()` и `int getDistanceTravelled()` и реализуйте его в двух классах:

- `ProductionRemoteControlCar` (серийная машина): `drive()` увеличивает пройденный путь на 10; есть методы `getNumberOfVictories()` и `setNumberOfVictories(int)`;
- `ExperimentalRemoteControlCar` (экспериментальная машина): `drive()` увеличивает путь на 20.

В классе `TestTrack` реализуйте статические методы: `race(RemoteControlCar car)` вызывает `drive()` у переданной машины; `getRankedCars(List<ProductionRemoteControlCar> cars)` возвращает список, отсортированный по убыванию числа побед. Для этого `ProductionRemoteControlCar` должен реализовать `Comparable<ProductionRemoteControlCar>`.

---

Источник: [Exercism — Java — Remote Control Competition](https://exercism.org/tracks/java/exercises/remote-control-competition) · © Exercism · [MIT](https://raw.githubusercontent.com/exercism/java/8e2a83395a5bfe9faedb3ce03b1fd85f0bcb5423/LICENSE) · условие пересказано на русском
