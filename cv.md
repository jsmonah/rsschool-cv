# Vitaly Monakhov
***
## Contacts
***
*   vitaly.monakhov@gmail.com
*   Skype: skymonah
*   Telegram: @jsmonah

## About Me
***
I love computers, technology and programs.
Communicative and responsive.
Experience in Windows administration, networking and software setup.
Basic knowledge of HTML, CSS and Javascript.
*	HTML
*	CSS 
*	Basic JavaScript 
*	Git / GitHub

## Code Examples
### javascript
```
import readlineSync from 'readline-sync';

const brainCalc = () => {
  console.log('Welcome to the Brain Games!');
  const userName = readlineSync.question('May I have your name? ');
  console.log(`Hello, ${userName}!`);
  console.log('What is the result of the expression?');
  const getRandomNumber = () => Math.floor(Math.random() * 100);
  const getRandomOperator = () => Math.floor(Math.random() * 3);
  let result;
  let youAnswer;
  for (let i = 1; i <= 3; i += 1) {
    const number1 = getRandomNumber();
    const number2 = getRandomNumber();
    const operator = getRandomOperator();
    switch (operator) {
      case 0:
        console.log(`Question: ${number1} + ${number2}`);
        result = number1 + number2;
        youAnswer = readlineSync.question('Your answer: ');
        if (Number(youAnswer) === result) {
          console.log('Correct!');
        } else {
          console.log(`'${youAnswer}' is wrong answer ;(. Correct answer was '${result}'.`);
          return console.log(`Let's try again, ${userName}!`);
        }
        break;
      case 1:
        console.log(`Question: ${number1} - ${number2}`);
        result = number1 - number2;
        youAnswer = readlineSync.question('Your answer: ');
        if (Number(youAnswer) === result) {
          console.log('Correct!');
        } else {
          console.log(`'${youAnswer}' is wrong answer ;(. Correct answer was '${result}'.`);
          return console.log(`Let's try again, ${userName}!`);
        }
        break;
      case 2:
        console.log(`Question: ${number1} * ${number2}`);
        result = number1 * number2;
        youAnswer = readlineSync.question('Your answer: ');
        if (Number(youAnswer) === result) {
          console.log('Correct!');
        } else {
          console.log(`'${youAnswer}' is wrong answer ;(. Correct answer was '${result}'.`);
          return console.log(`Let's try again, ${userName}!`);
        }
        break;
      default:
    }
  }

  return console.log(`Congratulations, ${userName}!`);
};

brainCalc();
```
## Experience
***
Service manager

Internet marketing, searching for and attracting customers.
Setting up and maintaining contextual advertising Google Ads and Yandex.
Estimating budgets and predicting results.

## Education
***
*	Higher
2005, East Ukrainian University
Economics and Entrepreneurship, Economic Cybernetics

## English
***
Level: B1 (Intermediate)