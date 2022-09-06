# Chistiakov Dmitriy #
*Frontend developer*

## Contacts ##
* Location: Russia, Voronezh
* Phone: +7 950 773 70 12
* Email: [dimitri.rim@yandex.ru](mailto:dimitri.rim@yandex.ru)
* Telegram: [https://t.me/DmitryChistiakov](https://t.me/DmitryChistiakov)
* GitHub: [https://github.com/DmitriyRim](https://github.com/DmitriyRim)

---
## About me ##

I always approach any question and various little things responsibly. At the university, he developed a project on the topic “Three-dimensional visualization of milling processing by means of WebGL".

Open to everything new. I always strive to gain new knowledge and skills.

---
## Skills ##

* HTML / CSS
* JavaScript
* Git, GitHub
* React / Redux

---
## Code Examples ##

Write a function that converts a number into an object. Passing a number in the range [0, 999] to the input,
we should get an object at the output in which the digits of the number are described in the corresponding properties:
- units (in the firstDigit property)
- tens (in the secondDigit property)
- hundreds (in the thirdDigit property)

```
function getDigitsOfNumber(num){
    let obj = {};
    if (isNumberCorrect(num)){
        let myNumber = `${num}`;
        obj['firstDigit'] = myNumber[2]? +myNumber[2]: 0;
        obj['secondDigit'] = myNumber[1]? +myNumber[1]: 0;
        obj['thirdDigit'] = myNumber[0]? +myNumber[0]: 0;
        return obj;
    }
}
function isNumberCorrect(num){
    return Number.isInteger(num) && num >= 0 && num < 1000;
}
console.log(getDigitsOfNumber(311));
```

## Work experience ##

- He developed a project at the university on the topic “Three-dimensional visualization of milling processing using WebGL".
- Portfolio site on React using the Mui Toolset - [https://dmitriyrim.github.io](https://dmitriyrim.github.io/resume)

---
## Education ##

- Voronezh State Technical University
- HTML Academy
- O'reilly Books
- Documentation

---
## Languages ##
- Russian - Native