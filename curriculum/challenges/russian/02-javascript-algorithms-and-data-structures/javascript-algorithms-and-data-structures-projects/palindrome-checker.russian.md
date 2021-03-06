---
id: aaa48de84e1ecc7c742e1124
title: Palindrome Checker
isRequired: true
challengeType: 5
videoUrl: ''
localeTitle: Palindrome Checker
---

## Description
<section id="description"> Возвращает <code>true</code> если данная строка является палиндром. В противном случае верните <code>false</code> . <dfn>Палиндром</dfn> - это слово или предложение, которое написано одинаково как вперед, так и назад, игнорируя знаки препинания, случай и интервал. <strong>Заметка</strong> <br> Вам нужно будет удалить <strong>все небуквенные символы</strong> (знаки препинания, пробелы и символы) и превратить все в один и тот же случай (нижний или верхний регистр), чтобы проверить палиндромы. Мы будем передавать строки с различными форматами, такими как <code>&quot;racecar&quot;</code> , <code>&quot;RaceCar&quot;</code> и <code>&quot;race CAR&quot;</code> среди других. Мы также передадим строки со специальными символами, такими как <code>&quot;2A3*3a2&quot;</code> , <code>&quot;2A3 3a2&quot;</code> и <code>&quot;2_A3*3#A2&quot;</code> . Не забудьте использовать <a href="http://forum.freecodecamp.org/t/how-to-get-help-when-you-are-stuck/19514" target="_blank">Read-Search-Ask,</a> если вы застряли. Напишите свой собственный код. </section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>palindrome(&quot;eye&quot;)</code> должен возвращать логическое значение.
    testString: 'assert(typeof palindrome("eye") === "boolean", "<code>palindrome("eye")</code> should return a boolean.");'
  - text: <code>palindrome(&quot;eye&quot;)</code> должен возвращать true.
    testString: 'assert(palindrome("eye") === true, "<code>palindrome("eye")</code> should return true.");'
  - text: <code>palindrome(&quot;_eye&quot;)</code> должен возвращать true.
    testString: 'assert(palindrome("_eye") === true, "<code>palindrome("_eye")</code> should return true.");'
  - text: <code>palindrome(&quot;race car&quot;)</code> должен возвращаться.
    testString: 'assert(palindrome("race car") === true, "<code>palindrome("race car")</code> should return true.");'
  - text: <code>palindrome(&quot;not a palindrome&quot;)</code> должен возвращать значение false.
    testString: 'assert(palindrome("not a palindrome") === false, "<code>palindrome("not a palindrome")</code> should return false.");'
  - text: '<code>palindrome(&quot;A man, a plan, a canal. Panama&quot;)</code> должен вернуться к истине.'
    testString: 'assert(palindrome("A man, a plan, a canal. Panama") === true, "<code>palindrome("A man, a plan, a canal. Panama")</code> should return true.");'
  - text: <code>palindrome(&quot;never odd or even&quot;)</code> должен возвращать true.
    testString: 'assert(palindrome("never odd or even") === true, "<code>palindrome("never odd or even")</code> should return true.");'
  - text: <code>palindrome(&quot;nope&quot;)</code> должен возвращать false.
    testString: 'assert(palindrome("nope") === false, "<code>palindrome("nope")</code> should return false.");'
  - text: <code>palindrome(&quot;almostomla&quot;)</code> должен возвращать значение false.
    testString: 'assert(palindrome("almostomla") === false, "<code>palindrome("almostomla")</code> should return false.");'
  - text: '<code>palindrome(&quot;My age is 0, 0 si ega ym.&quot;)</code> должен возвращать true.'
    testString: 'assert(palindrome("My age is 0, 0 si ega ym.") === true, "<code>palindrome("My age is 0, 0 si ega ym.")</code> should return true.");'
  - text: <code>palindrome(&quot;1 eye for of 1 eye.&quot;)</code> должен возвращать значение false.
    testString: 'assert(palindrome("1 eye for of 1 eye.") === false, "<code>palindrome("1 eye for of 1 eye.")</code> should return false.");'
  - text: '<code>palindrome(&quot;0_0 (: /-\ :) 0-0&quot;)</code> должен возвращать значение true.'
    testString: 'assert(palindrome("0_0 (: /-\ :) 0-0") === true, "<code>palindrome("0_0 (: /-\ :) 0-0")</code> should return true.");'
  - text: <code>palindrome(&quot;five|\_/|four&quot;)</code> должен возвращать значение false.
    testString: 'assert(palindrome("five|\_/|four") === false, "<code>palindrome("five|\_/|four")</code> should return false.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function palindrome(str) {
  // Good luck!
  return true;
}



palindrome("eye");

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
