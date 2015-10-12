## Variables Interactive Practice

### What is a Variable?
We use variables in programming to store pieces of data. Variables can store any type of data (strings, integers, floats, etc). When we name a variable, we use all lowercase letters. For example:
```js
var dog = "Fido";
```
In this example, all we've done is declare a varable `dog` an define that it stores the string `"Fido"`. Now, any time we tell our program to `dog`, it will return `Fido`.
```js
dog;
dog;
dog;
```
In this example, we should see `Fido` returned out three times.

What would happen if we did the following:
```js
var name = "Fido";
name = "Bessie";

name;
```
On the first line, we assigned the variable `name` to store `Fido`. On the next line, we reassigned the value of the variable `name` to store `Bessie`. Each variable can only store one value, so all we did was overwrite the value of the `name` variable. When we `puts name` on the last line, we will see `Bessie` printed out.

What if we want to have more than one word in our variable? Like:
```js
var best friend = "Steph";

best friend;
```
JavaScript gives us an error! `Uncaught SyntaxError: Unexpected identifier`. Ruby doesn't know what `best` is because of the space between the words `best` and `friend`. JavaScript doesn't recognize `best` as a key word  or as a data type, so it throws an error. It's just like when we're creating directories or files in the terminal, the space confuses the computer. Instead, replace spaces with underscores:
```js
var best_friend = "Steph";

best_friend;
```
###Let's practice!

What will be printed to the screen after running each of these? Talk to a partner and decide on an answer before running your code from a Ruby file that you create called `variables_practice.js`.
???
# Variables Practice

?: What is the outcome of running the code below?
```js
var a = 40;
var b = 322;

a * b
```
( ) 9000
( ) 15000
(X) 12880

?: What is the outcome of running the code below? 
```
var dog = "Little Bunny";
var cat = "Foo Foo";

dog + cat;
```
(X) "Little Bunny Foo Foo"
( ) "LittleBunnyFooFoo"
( ) dogcat

?: What is the outcome of running the code below?
```js
var snack = "Cheetos"

"My favorite snack is " + snack 
```
( ) My favorite snack isCheetos
(X) My favorite snack is Cheese
( ) myfavoritesnackischeetos

?: What is the outcome of running the code below?
```js
var first = "Amy";
var last = "Schumer";
var age = 34;

"The host of SNL is " + first + " " + last + " and she is " + age + " years old.";
```
(X) "The host of SNL is Amy Schumer and she is 34 years old."
( ) "The host of SNL is AMY SCHUMER and she is 34 years old."
( ) "The host of SNL is amy schumer and she is thiry-four years old."

?: What is the outcome of running the code below?
```js
var artist_first = "NiCKi"
var artist_last = "MiNaj"

"When I listen to " + artist_first.toUpperCase() + " " + artist_last.toLowerCase() + " I feel like my brain is melting."
```
( ) When I listen to NICKI MINAJ I feel like my brain is melting.
( ) When I listen to Nicki Minaj I feel like my brain is melting.
(X) When I listen to NICKI minaj I feel like my brain is melting. 

?: What is the outcome of running the code below?
```js
var name = "Allyson";
var age = 19;
var city = "Boston";

"Hi. I'm " + name.toUpperCase() + ". I'm from " + city.toLowerCase() + " and in ten years I'm going to be " + (age+10);
```
(X) "Hi. I'm ALLYSON. I'm from boston and in ten years I'm going to be 29"
( ) "Hi. I'm Allyson. I'm from Boston and in ten years I'm going to be twenty-nine"
( ) "Hi. I'm ALlYsOn. I'm from bOsToN and in ten years I'm going to be 29"


?: What would be the difference between the product and the sum?
Set `x` equal to 34679, `y` equal to 566 and `z`equal to 47. Set a variable equal to the product of these three numbers. Then set a variable equal the sum of the three numbers. Find the difference between the product and the sum.

( ) 35,292
(X) 922,495,466
( ) 922,466,495

???