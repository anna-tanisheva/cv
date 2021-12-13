# Anna Tanisheva

![Anna Tanisheva](assets/8bd28473-025e-42b5-8bb2-cc0a7bcf550a.jpg)

## Contacts:
**email**: anna-tanisheva@yandex.ru;

**tel**: +375291187843;

**skype**: eyeinthesky42;

**discord**: Anna Tanisheva (anna-tanisheva);

## Summary:
My name is Anna Tanisheva. I live in Minsk and I'm working on new career path.

I graduated as a lawyer in 2007. Most of my working experience is connected with casino job.

I have short experience in **web-developing: 2017, half a year I was working for a advertising agency "Ashwood Company".**
I had to leave that job because I needed to move to another city.

I'm a reliable, tenacious and optimistic person. I easily find common ground with people and I'm used to work hard to achieve my goals. I like learning something new and I'm interested in web developing.

## Technologies:
HTML, CSS,

Vanilla JS, JQuery,

TweenMax animation,

Git

## My Code example (Codewars):
>In this kata you are required to, given a string, replace every letter with its position in the alphabet.
If anything in the text isn't a letter, ignore it and don't return it.
"a" = 1, "b" = 2, etc.
Example
alphabetPosition("The sunset sets at twelve o' clock.")
Should return "20 8 5 19 21 14 19 5 20 19 5 20 19 1 20 20 23 5 12 22 5 15 3 12 15 3 11" (as a string)

          function alphabetPosition(text) {
            let newText = '';
            text = text.toLowerCase();
            for (i in text) {
              if (text[i].charCodeAt() > 96 && text[i].charCodeAt() < 123) {
                newText += text[i].charCodeAt()-96 + ' '
              } else {
                continue;
              }
            }
            text = newText.trim();
            return text;
          }

