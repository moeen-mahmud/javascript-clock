# A Drum Machine Using Vanilla JS

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgement](#acknowledgement)

## Overview

### The challenge

User should be able to see a local time giving clock which is like a wall clock.

### Screenshot

![Desktop View](./screenshot/js-clock.gif)

- Solution URL: [Git Repo](https://github.com/moeen-mahmud/javascript-clock)
- Live Site URL: [Live Site](https://javascript-clock-dun.vercel.app/)

## My Process

### Built With

- HTML5 markup
- JavaScript
- Document Object Model

### What I learned

This project was very interesting one. I was able to learn a handfull of things, especially, the `date()` method and some tricky css transition.

```javascript
const seconds = now.getSeconds();
const secondsDegrees = (seconds / 60) * 360 + 90;
secondHand.style.transform = `rotate(${secondsDegrees}deg)`;
```

### Continued Development

This project is from [Wes Bos's 30 JavaScript](https://javascript30.com/) course. It is the second one and an awesome one!

### Useful resources

- [Mozilla Developer Network](https://developer.mozilla.org/en-US/)
- [JavaScript 30](https://javascript30.com/)

## Author

- Twitter - [moeen_mahmud](https://twitter.com/moeen_mahmud)

## Acknowledgement

A huge thanks to [Wes Bos](https://javascript30.com/).
