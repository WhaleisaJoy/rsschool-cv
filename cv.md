# Mariia Makarova

## Contact information

**Phone:** +79159983079\
**E-mail:** [afterlifelineonomega\@gmail.com](mailto:afterlifelineonomega@gmail.com)\
**GitHub:** [WhaleisaJoy](https://github.com/WhaleisaJoy)\
**Telegram:** [WhaleJoyOcean](https://t.me/whalejoyocean)\
**LinkedIn:** [maria-makarova](https://www.linkedin.com/in/maria-makarova-580a12235/)\
**CodePen:** [WisaJofO](https://codepen.io/WisaJofO)

## About Me

Hi! I work as an e-learning developer. I create e-learning courses and browser games. Coding is not just my job but also my hobby. I enjoy watching videos about it, read articles, learn new ways to optimise my everyday tasks and solve problems. My goal is to start working on interesting projects using modern frameworks like React.

## Skills

- HTML5
- CSS (SASS, BEM)
- JS, TS, JSON
- React, Redux, Next JS (fundamentals)
- Phaser 3
- GitHub, GitLab
- Figma, Photoshop

## Code examples

**Task:** build a pyramid-shaped tower, as an array/list of strings, given a positive integer `number of floors`. A tower block is represented with `"*"` character.

**Solution:**

```
function towerBuilder(nFloors) {
  const floorStep = 2;
  const maxSymbols = nFloors * floorStep - 1;

  return Array(nFloors).fill().map((elem, index) => {
    const repeat = index * floorStep + 1;
    const emptySpaces = maxSymbols - repeat;

    return ' '.repeat(emptySpaces / 2) + '*'.repeat(repeat) + ' '.repeat(emptySpaces / 2);
  });
}
```

## Work experience

- **2015 - 2016** _Developer_
- **2016 - 2018** _E-learning Developer_ Create e-leaning courses (HTML, CSS, JS)
- **2018 - 2022** _E-learning Developer_ Create e-leaning courses and browser games (HTML, CSS, JS, Phaser3)
- **2022 - Present** _E-learning Developer_ Create e-leaning courses and browser games (HTML, CSS, JS, Phaser3)

## Education

**University:**

Demidov Yaroslavl State University

- sociology, 2011-2015 (MA)
- sociology, 2015-2017 (BA)

**Courses:**

- HTML Academy
  - HTML &CSS. Professional Website Coding, 2020
  - HTML &CSS. Adaptive Website Coding and Automation, 2021
  - JavaScript.Professional Development of Web Interfaces, 2021
  - JavaScript.Architecture of Front-end Applications, 2021
  - React.Development of Complex Front-end Applications, 2024
- RS School, JavaScript/Frontend (Stage 1), 2025

## Languages

- Russian (Native)
- English (B2)
