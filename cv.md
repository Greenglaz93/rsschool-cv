## [rsschool-cv](rsccool-cv)


# Valeriya Zaytseva

## My Contact Info

* **Current location:**  Astrakhan, Russia
* **Phone:** +7 917 1984991
* **E-mail:** [greenglaz2011@gmail.com](greenglaz2011@gmail.com)
* **LinkedIn:** [greenglaz](www.linkedin.com/in/greenglaz)
* **GitHub:** [Greenglaz93](https://github.com/Greenglaz93)


## Summary
I graduated from the "Front-end developer" profession at the [HTML Academy](https://htmlacademy.ru/profile/greenglaz/certificates) 
and am in the queue for an internship. So I spend all my free time on learning.
I’m interested in Web Development because this occupation provides endless possibilities for professional growth,
besides there’s a huge amount of free high quality resources for self-education and a large community of developers.

I believe, that my ability to learn and to gain new skills will lead me through this path of becoming a proficient Frontend Developer.

## Skills

* HTML
* CSS (Preprocessor SCSS, BEM methodology).
* JavaScript (Fundamentals, Functional Programming, Asynchronous JavaScript, ES6+, DOM), JSON.
* Version control: Git (remote service GitHub).
* Module Bundlers: Gulp.
* Windows OS
* Figma, Adobe Photoshop, Adobe Illustrator, Zeplin, Avocode, CorelDraw

## Code examples

```js
const createUniqueIdGeneratorFromRange = (min, max) => {
  const previousValues = [];

  return function () {
    let currentValue = getRandomIntInclusive(min, max);
    if (previousValues.length >= (max - min + 1)) {
      throw new Error('Перебраны все числа из диапазона');
    }
    while (previousValues.includes(currentValue)) {
      currentValue = getRandomIntInclusive(min, max);
    }
    previousValues.push(currentValue);
    return currentValue;
  };
};
```
## Education

* **HTML Academy**
    * [Course "Frontend-developer"](https://htmlacademy.ru/profession/frontender)
* **RS Schools**
    * Course «JavaScript/Front-end. Stage 0» (in progress)

## Experience

* I have little experience in JS and Frontend development. I have worked in the team on several small projects and currently working.

## Languages

- Russian - Native
- English - Intermediate/Upper-intermediate(CEFR B2) (according to the online test at www.efset.org)
