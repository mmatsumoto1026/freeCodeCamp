---
id: 5900f4591000cf542c50ff6c
title: 'Завдання 237: маршрути на ігровій дошці 4 × n'
challengeType: 1
forumTopicId: 301882
dashedName: problem-237-tours-on-a-4-x-n-playing-board
---

# --description--

Нехай $T(n)$ буде кількістю маршрутів на ігровій дошці 4 × $n$ так, що:

- Маршрут починається у верхньому лівому куті.
- Маршрут складається з ходів вгору, вниз, вліво або вправо на одну клітинку.
- Маршрут проходить по кожному квадрату лише один раз.
- Маршрут закінчується в нижньому лівому куті.

На малюнку зображено один із маршрутів на дошці 4 × 10:

<img alt="один із маршрутів на дошці 4 х 10" src="https://cdn.freecodecamp.org/curriculum/project-euler/tours-on-a-4-x-n-playing-board.gif" style="background-color: white; padding: 10px; display: block; margin-right: auto; margin-left: auto; margin-bottom: 1.2rem;" />

$T(10)$ дорівнює 2329. Чому дорівнює $T({10}^{12})$ modulo ${10}^8$?

# --hints--

`toursOnPlayingBoard()` має повернути `15836928`.

```js
assert.strictEqual(toursOnPlayingBoard(), 15836928);
```

# --seed--

## --seed-contents--

```js
function toursOnPlayingBoard() {

  return true;
}

toursOnPlayingBoard();
```

# --solutions--

```js
// solution required
```
