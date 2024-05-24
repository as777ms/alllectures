# WHAT IS ?
![js](./jss.jpg)



#### JavaScript was invented by Brendan Eich in 1995. It was developed for Netscape 2, and became the ECMA-262 standard in 1997.


#### JS
>[!TIP]
>JavaScript is a scripting or programming language that allows you to implement complex features on web pages---every time a web page does more than just sit there and display static information for you to look at `i mean it will not update that page` And also whant to explain that JavaSript can't work without HTML and CSS 

* `HTML` is the markup language that we use to structure and give meaning to our web content, for example defining paragraphs, headings, and data tables, or embedding images and videos in the page.
* `CSS` is a language of style rules that we use to apply styling to our HTML content, for example setting background colors and fonts, and laying out our content in multiple columns.
* `JavaScript` is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)

if you whant to gain more information about this programming language you can follow to this <a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript">Web</a> <a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript">Page</a>

>JavaSript Является реализацией спецификации ECMAScript (стандарт ECMA-262[2]).      

>[!TIP]
> in JavaSript we have got 3 kind of keywords
`var` `let` and `const`



>[!TIP]

in JS we have got 7 primitives and more over objects
```js
undefined
null
number
string
booleon
symbol
bigInt
```
![primit](./primitives)
it was primitives in JS 
>![jnfkml](./primitveandobject.png)

>Operators in JavaScript
``` js
+ 	Addition
- 	Subtraction
* 	Multiplication
** 	Exponentiation (ES2016)
/ 	Division
% 	Modulus (Division Remainder)
++ 	Increment
-- 	Decrement
```
```js
Operator     Examples          Same As
=             x = y 	        x = y
+= 	      x += y 	        x = x + y
-= 	      x -= y 	        x = x - y
*= 	      x *= y 	        x = x * y
/= 	      x /= y 	        x = x / y
%= 	      x %= y 	        x = x % y
**= 	      x **= y 	        x = x ** y
```

>JavaScript Comparison Operators
Operator 	Description
``` js
== 	equal to
=== 	equal value and equal type
!= 	not equal
!== 	not equal value or not equal type
> 	greater than
< 	less than
>= 	greater than or equal to
<= 	less than or equal to
? 	ternary operator
```

>JavaScript Logical Operators
Operator 	Description

``` js
&& 	logical and
|| 	logical or
! 	logical not
```

>
JavaScript Type Operators
Operator 	Description
``` js
typeof 	Returns the type of a variable
instanceof 	Returns true if an object is an instance of an object type
```


>[!TIP]
>The `if/else` statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed. The if/else statement is a part of JavaScript's `"Conditional"` Statements, which are used to perform different actions based on different conditions.


```js
function condition(a) {
    if(a<=14){
        return "Sorry but you are not to old"
    }
    else{
        return "Yes you are exist"
    }
}
console.log(condition(6));//Sorry but you are not to old
```

>[!TIP]
>The conditional (ternary) operator is the only JavaScript operator that takes three operands: a condition followed by a question mark ( ? ), then an expression to execute if the condition is truthy followed by a colon ( : ), and finally the expression to execute if the condition is falsy.

``` js
function condition(a) {
    return a<=14 ? "Sorry but you are not to old" : "Yes you are exist"
}
console.log(condition(6));//Sorry but you are not to old
```

>[!TIP]
>The switch statement `executes a block of code depending on different cases`. The switch statement is a part of JavaScript's "Conditional" Statements, which are used to perform different actions based on different conditions. Use switch to select one of many blocks of code to be executed.

``` js
let expr = 'Papayas';
switch (expr) {
  case 'Oranges':
    console.log('Oranges are $0.59 a pound.');
    break;
  case 'Mangoes':
  case 'Papayas':
    console.log('Mangoes and papayas are $2.79 a pound.');
    // Expected output: "Mangoes and papayas are $2.79 a pound."
    break;
  default:
    console.log(`Sorry, we are out of ${expr}.`);
}
```

>[!TIP]
>for - loops through a block of code a number of times. for/in - loops through the properties of an object. for/of - loops through the values of an iterable object. while - loops through a block of code while a specified condition is true.
and hep here i said something about `for/in` it we will learn about it in object


```js
function condition(a) {
    let cnt=0
    for(let i=0; i<=a; i++){
         cnt+=i
    }
    return cnt
}
console.log(condition(6));//21
```

>while and do-while in doing the same thing in like a for in JS `they create loop`

>[!TIP]
>Function Declaration in JS
``` js
function declaration(a,b) {
    return a+b
}
console.log(declaration(2,3));//5
```

>[!TIP]
>Function Expression (Arrow)
``` js
let a=(a)=>{
    return a+1
}
console.log(a(4));//5
```

>[!TIP]
>Function Expression (Anonymous)
``` js
let anon = function() {
  alert('I am anonymous');
}
anon(); //This is anonymous function
```
>[!TIP]
>IIFE (Immediatly invoked function expression)
``` js
(function() {
let numb = 4 + 4;
console.log(numb);
})();//8
```




# Fibonacci Numbers
#### Fibonacci 
#### Fibonacci raqam avalani bor dar Hinduston soxta wuda bud 200 sol PC (pew az millod) lekin yak waxsi Itoliyoi Leonardo Pisano Fibonacci (1170–1240 yo 1250 murd) wai Fibonacciro ba jaxon introduce kard wa inro Arabic number paydarpayi menomidand (poryadok) Fibonacci-ro xamchun dar nature dar priroda istifoda mebarand (meguyand ki tabiat az Fibonacci vobasta ast) baroi chi nomwa Fibonacci monday? baroi on ki bo zaboni Itoliyoi “filius Bonacci” mewavad dar Itoliyoi in nom manoi pisari Bonachi menomand yo agar kak prozvishe `udacha`  meguyand

>[!TIP]
>Fibonacci numbers — это последовательность целых чисел, которая `начинается с 0 и 1`. Каждое следующее число в последовательности является `суммой двух предыдущих чисел`.Вот некоторые примеры чисел в последовательности: `0, 1, 1, 2, 3, 5, 8, 13, 21, 34` и так далее.Fibonacci numbers были впервые обнаружены итальянским математиком Леонардо Фибоначчи в 13 веке.
>![fibonacci](./fibonaacci)


#### Vot eto tip fibonacci primer ot 0 do 9
![f](./number)
AS WE SAID IN THE TOP `Числа Фибоначчи — это последовательность чисел, где каждое число является суммой двух предыдущих чисел` XAR YAK 2 RAQAMI PEWINA BA YAKDIGAR JAM MEWAVAND

## Demo Video

[Watch the demo video](./What_is_the_Fibonacci_Sequence_&_the_Golden_Ratio_Simple_Explanation.mp4)

<video width="320" height="240" controls>
  <source src="./What_is_the_Fibonacci_Sequence_&_the_Golden_Ratio_Simple_Explanation.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

RIGHT NOW YOU LEARNED HOW TO SOLVE TASKS BY THAT WE NEED TO KNOW MORE INFORMATION ABOUT FIBONACCI number <a href="https://youtu.be/r3BjNKfQaR0?si=I9b9qyw9UScnPruM">go to this link and learn</a>




<h2>What are <span style="color:pink">Hoisting</span> and <span style="color:pink">Scope</span> in JavaScript?</h2>


####  Podnytaie ili Hoisting - eto mekhanizm v JS, v kotorom peremenie i obyavlennie function-i peredvigaytsya vverkh ⬆️ `yanne vaqte ki kodi mo ba bolo meravad dar oblast vidimost pesh az on ki kod ijro karda meshavad`

>[!TIP]
>hoisting yane boloravi dar `function declaration` dar lyuboi moment kor mekunda chi mo functionro dar bolo faryod kunem chi dar tag ammo dar `function expression` va `IIFE` mo tanxo dar poyon Hoisting karda metavon chun ki `TypeError and ReferenceError` medixad
:Misol

``` js
console.log(expression(2,2));//ReferenceError: Cannot access 'declaration' before initialization
let expression=function(a,b){
    return a*b
}
```

>[!TIP]
>ammo dar `function declration` hoisting mewavad 

:Misol

``` js
function declration(a,b) {
    return a*b
}
console.log(declration(2,2));//4
```

# 👀 Рассмотрим следующий пример:


```js
var myname = "John";
function fn() {
  console.log(myname);
  var myname = "Tom";
  console.log(myname);
}

fn();

// undefined
// Tom
```

>[!TIP]
>`var имеет область действия функции;
объявления var поднимаются, но не инициализируются.`

```js
console.log(name); // undefined
var name = "Alex";//baroi chi underfined baroi on ki in var hast hamewa hoist meshavad ammo dar tori var log nameshavad
```
```js 
var name;
console.log(name); // undefined
name = "Alex";
```
 # const and let 

>[TIP]
# const и let имеют область видимости блока.

```js
{
  console.log ( x )
  // [ временная мёртвая зона ][tdz][temporarl dead zone]
  let x = 10 // Объявленные с помощью let, будут недоступны до тех пор, пока выполнение кода не дойдёт до места фактического объявления переменной
}
```
# farqitawon dar in jo faxmonda wudaast
```js
console.log(a); // undefined
var a = 1;

console.log(b); // ReferenceError: Cannot access 'b' before initialization
let b = 2;

console.log(c); // ReferenceError: Cannot access 'c' before initialization
const c = 5;
```


<h2 style="color:yellow">Введение в JavaScript SCOPE</2>
<h6 style="color:brown">scope in oblast vidimosti dar JS meboshad</h6>


* Область видимости или Scope
* Глобальная область видимости или Global Scope
* Локальная область видимости или Local Scope
* Область видимости функции
* Область видимости блока
* Лексическая область видимости
* Динамическая область видимости

``` diff
-Область видимости (scope) определяет видимость или доступность переменной (другого ресурса) в области твоего кода.
```
```js

var num = 5;
console.log(num);   // 5

function getNum(){
  console.log(num); // num доступен здесь
}

getNum();           // 5 i chiz faqat var da mumkinai digaroda ne⬆️
```
 

# ⬆️   i GLOBAL SCOPE ai 


#### dar js mo dorem
# module scope
# block scope
# function scope
# global scope 

#### local scope peremennixoi daruni function a megan `local ni oblast megan ujara xar yak function oblast vidimosti xcha dora` ``Одна и та же переменная может использоваться в разных функциях, поскольку они связаны с соответствующими функциями и не являются взаимно видимыми.`yak peremenira dar chand funtion istifoda burda meshiday`


``` js
// Глобальная область

function foo1(){
    // Локальная область 1
  function foo2(){
    // Локальная область 2
  }
}

// Глобальная область
function foo3(){
  // Локальная область 3
}

// Глобальная область
```

>Локальная область видимости может быть разделена на область видимости функции и область видимости блока. Концепция область видимости блока или block scope была представлена в ECMAScript6 (ES6) вместе с новыми способами объявления переменных - const и let.

# Область видимости функции
> var a function scope am megan baroi on ki var lyuboijo rafta metona lekin var-a tolko function qapida metona

``` js
function foo(){
  var num = 10;
  console.log('inside function: ', num);
}

foo();                   // inside function: 10
console.log(num);       // ReferenceError: num is not defined
```

if for block scope


# JavaScript String & Math Methods
>There may come various instances where we need to manipulate strings in it.`krch dar zindagi misol vaqte ki wumo bo js kro mekuned yagon zadacha meoyad ki wumo dar in xolat bo string kor kunad yane vairon manipulirovat kardanawro yod gired in kor xele duwvor ast ba vositai for (baroi xamin methpdxo baromadand to in ki kori moro osoon kunand)`


**_So, let’s discuss the basic string methods in JavaScript._**

 * 1) Length Method
* 2) CharAt Method
* 3) EndsWith Method
* 4) Includes Method
* 5) IndexOf Method
* 6) Match Method
* 7) Repeat Method
* 8) Replace Method
* 9) Slice Method
* 10) Split Method
* 11) StartsWith Method
* 12) Substr Method
* 13) Substring Method
* 14) ToLowerCase Method
* 15) ToUpperCase Method
>Here, I have mentioned 15 string methods that are commonly used in javascript. Let’s discuss them in detail. i lenghta return mekna dazhe spaceoi xoliwa xisob mekna

# 1) Length Method
>methodi length ro baroi xisob kardani masofai string istifoda mebarand
⬇️ sintaxisaw
```js
let string.length;
```
```js
let str = "Hello Cybrosys";
let str_len = str.length;
console.log("length", str_len);//length 14
```

# 2)CharAt method
>methidi charAt da mo indexi darkori mona metem mebrora xarfa (index ai 0 sar mewava) baroi giriftani 1 xarf mo 0 metem dar daruni parametroi charAt
⬇️ sintaxsisw
```js
string_variable.charAt(‘index’);
```
```js
let str = "Hello Cybrosys";
let char_at = str.charAt(6);
console.log(char_at); //C chiba C baroi on ki spaceora xisob kadai znachit
```

# 3) EndsWith Method
>methodi endWith returnw true yo false ai aga biyova oxiraki xamu text ba xamu parametri doxil kadagii mo tugri bgira
⬇️ syntexisw
```js
string_variable.endsWith(‘characters’);
```
```js
let str = "Hello Cybrosys";
let is_last = str.endsWith('sys');
console.log(is_last);//true
```

```js
let str = "Hello Cybrosys";
let is_last = str.endsWith('C');
console.log(is_last);//false meta baroi on ki oxiri i text C nest (znachit rangi includes nest)
```

# 4) Includes Method
>i true you false mebrora mekova agar youft true aga nayoft false ida rangi unau torgi farq nadora chi i da oxirai chi da mobain chi da aval agar xamu chi da text bowa true false wa mebrora
⬇️ syntexisw
```js
string_variable.includes(‘characters’);
```
```js
let  str = "Hello Cybrosys";
let is_incl = str.includes('sys');
console.log(is_incl);//true
```

```js
var str = "Hello Cybrosys";
var is_incl = str.includes('xyz');
console.log(is_incl);//false meta baroi ki itari chi nest
```

# 5) IndexOf Method
>IndexOf method indexi xamu xarfi da parametr mondagii mora mebrora aga nayoft -1 mebrora
⬇️ syntexisw
```js
string_variable.indexOf(‘characters’);
```
```js
var str = "Hello Cybrosys";
var index_char = str.indexOf('sys');
console.log(index_char);//11 meta baroi ki xarfi avalwa mebina agane boyad 13 bta ku
```
# 6) Match Method
>i masiv mebrovardai indexw qati xamu (chze ki mo da parametr drovardem indexwa) bad bo input: "xamu texta polni xcha" bad bo groups: undefined mebrovardai aga nayova null mebrora

```js
string_variable.match(‘expression’);
```
```js
let str = "Hello Cybrosys";
let match_expr = str.match("sys");
console.log(match_expr);//[ 'sys', index: 11, input: 'Hello Cybrosys', groups: undefined ]
```


# 7) Repeat Method
>ira megem ki chanbor repeat kna i takror mekna xamu texta yo xarfa
```js
string_variable.repeat(‘count’);
```
```js
var str = "Hello Cybrosys";
var repeat_expr = str.repeat(3);
console.log(repeat_expr);//Hello CybrosysHello CybrosysHello Cybrosys
```

# 8) Replace Method
>i chira ba chi aliw knak methodai 2 parametr megira chira ba chi aliw kna (kadom xarfa yo kalimara ba chi) aga nayoft xamu chzi aliw mekadagira xdi stringa return mekna

```js
str = "Hello Cybrosys";
let replace_expr = str.replace('Hello', "Anisa");
console.log(replace_expr);//Anisa Cybrosys
```
 
# 9) Slice Method
>ida 2 ta argument roi meknem start end ai kujo sar wava to kjo brava (ba indexi xarfo metem) i -0 ram qabul mekna rangi substringai prosto u - 0 qabul namekna aga 1 argument roi knem ai sarwavi to ixiri stringa mebrora
```js
let str = "Hello Cybrosys";
let slice_expr = str.slice('6', '11');
console.log(slice_expr);//Cybro
```

# 10) Split Method
> i stringa mesaiv mekna vobasta ba on ki mo chxeli bgemw aga ("") xamai xarfora judo mekna aga (",") cherez vergul judowon mekna bo ya chii diga i space oram judo mekna 
```js
var str = "Hello Cybrosys";
var split_expr = str.split('');
console.log(split_expr);//['H', 'e', 'l', 'l','o', ' ', 'C', 'y','b', 'r', 'o', 's','y', 's']
```

# 11) StartsWith Method
>i true you false mebrora agar da sarwavii string xamu chizi roi kadagii mo bowa agar nabowa false i indexam kak 2 parametr megira indexwa yoft true false mega

```js
var str = "Hello Cybrosys";
var start_expr = str.startsWith("He");
console.log(start_expr);//true
```

```js
var str = "Hello Cybrosys";
var start_expr = str.startsWith("Cy", 6);
console.log(start_expr);//ijada true meta chixele ki guftem mesanja indexw tugriay ba xamu
```

# 12) Substring Method
>chi xele ki guftem i rangi slice ai tolko u -minusa qabul mekna i ne start end dora
```js
var str = "Hello Cybrosys";
var substring_expr = str.substring(13, 5);
console.log(substring_expr);//Cybrosy
```


# 13) ToLowerCase Method
>i past mekna vesi xamu xarfora
```js
var str = "Hello Cybrosys";
var toLowerCase_expr = str.toLowerCase();
console.log(toLowerCase_expr);//hello cybrosys
```

# 14) ToUpperCase Method
>i baland mekna vesi xamu xarfora
```js
var str = "Hello Cybrosys";
var toUpperCase_expr = str.toUpperCase();
console.log(toUpperCase_expr);//HELLO CYBROSYS
```


### Math Methods
# 1) Math.abs()
>i minusara + mekna
```js
Math.abs(-1); // 1
```
# 2) Math.floor()
>i xamu adad azdax doram bowa xamu adada niwon meta to xdi adada kalonw nawava maqsad azdaxdorakwa megira
```js
console.log(Math.floor(5.95));
// Expected output: 5
```
# 3) Math.min()
>i xurdtarina da baini xamu adad mebrora
```js
console.log(Math.min(1, 3, 2));
// Expected output: 1
```

# 4) Math.max()
>i kalontarina da baini xamu adad mebrora
```js
console.log(Math.max(1, 3, 2));
// Expected output: 3
```

# 5) Math.pow()
>i darajai xamu adata mebrora 2 parametr megira 1 kadom adad 2 darajaw
```js
console.log(Math.pow(7, 3));
// Expected output: 343
```

# 6) Math.random()
> i randomno mebrora ai 0 to 0 az mlrd baroi ki moda adadi darkorimona bubrora darkorai ki ura ba i zar knm
```js
let a=10
let a2=(Math.floor(Math.random()*10))
console.log(a2);//it will return everything till 10
```

# 7) Math.round()
>ida xami azdax 1 ki wid uzhe kalon mexisoba raqama
```js
console.log(Math.round(0.9));
// Expected output: 1
```


# A closure-Замыкание — это
>[!TIP]
>Замыкание — это комбинация объединенной (заключенной) функции со ссылками на ее окружающее состояние (лексическое окружение). Другими словами, замыкание дает вам доступ к области видимости внешней функции из внутренней функции. В JavaScript замыкания создаются каждый раз при создании функции, во время ее создания.(`maqsad ai daruni functioni dar daruni return bdagi metonem functioni 1 bdroem 2 namudi closure soxtan xast 1 giw 2 function drun ba drun 3 giw da daruni return arrow function qati`)



```js
function init() {
  var name = "Mozilla"; // name is a local variable created by init
  function displayName() {
    // displayName() is the inner function, that forms the closure
    console.log(name); // use variable declared in the parent function
  }
  displayName();
}
init();
```
>`init()` создает локальную переменную с именем `name` и функцию `displayName()`. Функция `displayName()` — это внутренняя функция, определенная внутри `init()` и доступная только внутри тела функции `init()`. Обратите внимание, что функция `displayName()` не имеет собственных локальных переменных. Однако, поскольку внутренние функции имеют доступ к переменным внешних функций, `displayName()` может получить доступ к имени переменной, объявленной в родительской функции init().

# Here is a example of closure in return
```js
function makeAdder(x) {
  return function (y) {
    return x + y;
  };
}
let add5 = makeAdder(5);
let add10 = makeAdder(10);
console.log(add5(2)); // 7
console.log(add10(2)); // 12
```
>В этом примере мы определили функцию makeAdder(x), которая принимает один аргумент x и возвращает новую функцию. Возвращаемая функция принимает один аргумент y и возвращает сумму x и y.



>По сути, makeAdder — это фабрика функций. Он создает функции, которые могут добавлять определенное значение к своему аргументу. В приведенном выше примере фабрика функций создает две новые функции: одну, которая добавляет пять к своему аргументу, и другую, которая добавляет 10.


```js
function foo() {
    let b = 1;
    function inner() {
        return b;
    }
    return inner;
}
let get_func_inner = foo();

console.log(get_func_inner());
console.log(get_func_inner());
console.log(get_func_inner());
```
* Преимущества Zamikaniy
* Varieblxoi ki da closure soxranit kadagien metonen lyuboi moment istifoda baren oсохранить состояние, которое вы сможете использовать позже.
* Они помогают удалить лишний код.
* Они помогают поддерживать `модульный код`.

* Недостатки Zamikaniya
* Слишком большое количество замыканий может замедлить работу вашего приложения. На самом деле это вызвано дублированием кода в памяти. `rost mega vaqti ran kardanoi kodda mechaspa`
* ⬇️⬇️⬇️⬇️ dar vaqti ran kardani inamin kod
``` js
for (let id = 0; id < 3; id++) {
    // The use of 'let' creates a block-scoped variable, fixing the closure issue.
    // Now each setTimeout callback captures the correct value of 'id'.
    setTimeout(function () {
      console.log('seconds: ' + id);
    }, id * 1000);
  }
```
```js
function foo(outer_arg) {

    function inner(inner_arg) {
        return outer_arg + inner_arg;
    }
    return inner;
}
let get_func_inner = foo(5);

console.log(get_func_inner(4));//9
console.log(get_func_inner(3));//8
```
>>> closure is look like this function
![closure](./closure)
### Запустите код, используя эту ссылку JSFiddle, и обратите внимание, что оператор console.log() в функции displayName() успешно отображает значение переменной name, которая объявлена ​​в ее родительской функции. Это пример лексической области видимости, который описывает, как синтаксический анализатор разрешает имена переменных, когда функции вложены. Слово «лексический» относится к тому факту, что лексическая область видимости использует место объявления переменной в исходном коде, чтобы определить, где эта переменная доступна. Вложенные функции имеют доступ к переменным, объявленным в их внешней области видимости.
>В этом конкретном примере область называется областью функции, поскольку переменная доступна и доступна только внутри тела функции, где она объявлена.
```js
let message = 'Hello';

function buildGreeting() {
  let audience = 'World';
  let message = 'Hello';  // Duplicate variable declaration
  function buildGreeting() {
    let audience = 'World';
    console.log(message + ' ' + audience);
  }
}
console.log(audience);  // 'audience' is not defined in this scope WHY IT SHOULD SAY THAT AUDIANCE IS NOT DEFINED
```


#### Because here we called all this function
```js
function buildGreeting() {
let message = "Hello";
function greetUser() {
console.log(message);
}
return greetUser;
}
let hello = buildGreeting();
hello();  //Hello 
```

>[!TIP]
>Variables created without a declaration keyword (var, let, or const) are always global, even if they are created inside a function.
```js
function myFunction() {
  a = 4;
}
```
>baroi inami Let wida i 1 1 1 merava baroi ki leta da daruni i function soxtem na inki global⬇️
```js
// Initiate counter
let counter = 0;

// Function to increment counter
function add(a) {
 return counter += 1;
}

// Call add() 3 times
console.log(add());//1
console.log(add());//1
console.log(add());//1

// The counter should now be 3 
```
