# SOLVED-TASKS

```javascript
let a = 123;
```

[Multiply](https://www.codewars.com/kata/50654ddff44f800200000004)
```javascript
function multiply (a, b) {
  return a * b;
}
```

[Function 1 - hello world](https://www.codewars.com/kata/523b4ff7adca849afe000035)
```javascript
function greet () {
var str = 'hello world!';
  console.log(str);
  return str;
}
```

[Training JS #1: create your first JS function and print "Helloworld!"](https://www.codewars.com/kata/571ec274b1c8d4a61c0000c8)
```javascript
function helloWorld() {
var str = "Hello World!";
console.log(str);
}
```

[Beginner Series #2 Clock](https://www.codewars.com/kata/55f9bca8ecaa9eac7100004a)
```javascript
function past(h, m, s) {
  return (h * 3600000 + m * 60000 + s * 1000);
}
```

[Grasshopper - Make change](https://www.codewars.com/kata//560dab9f8b50f89fd6000070)
```javascript
const money =10;
const candy = 1.42;
const chips = 2.40;
const soda = 1;
const change = money - candy - chips -soda;
console.log(change);
```

[Grasshopper - Basic Function Fixer](https://www.codewars.com/kata//56200d610758762fb0000002)
```javascript
function addFive(num) {
  var total = num + 5;
  return total;
}
```
[Training JS #2: Basic data types--Number](https://www.codewars.com/kata//571edd157e8954bab500032d)
```javascript
var v1 = 50; v2 = 100, v3 = 150, v4 = 200, v5 = 2, v6 = 250;
function equal1() {
  var a = v1;   
  var b = v1;   
  return a + b;
}
//Please refer to the example above to complete the following functions
function equal2() {
  var a = v4;
  var b = v2;
  return a - b;
}
function equal3() {
  var a = v1; 
  var b = v5;
  return a * b;
}
function equal4() {
  var a = v4; 
  var b = v5;
  return a / b;
}
function equal5() {
  var a = v6; 
  var b = v3;
  return a % b;
}
```

[For Twins: 2. Math operations](https://www.codewars.com/kata/59c287b16bddd291c700009a)
```
function iceBrickVolume(radius, bottleLength, rimLength) {
  let v = (bottleLength - rimLength) * Math.sqrt(2 * Math.pow(radius,2)) * Math.sqrt(2 * Math.pow(radius,2));
  return Math.round(v);
}
```

[Third Angle of a Triangle](https://www.codewars.com/kata/5a023c426975981341000014/train/javascript/5e0067487f79bd00224aed0a)
```
function otherAngle(a, b) {
  return 180 - a - b;
}
```

[Sum of angles](https://www.codewars.com/kata/5a03b3f6a1c9040084001765/train/javascript/5e00699adf8a1200166c854b)
```
function angle(n) {
 let sumAngle = 180 * (n - 2); 
 return sumAngle;
}
```

[Breaking chocolate problem](https://www.codewars.com/kata/534ea96ebb17181947000ada)
```
function breakChocolate(n,m) {
  const crack = (n * m) - 1;
  if (n > 0 && m > 0)  return crack;
  else return 0; 
}
```

[I love you, a little , a lot, passionately ... not at all](https://www.codewars.com/kata/57f24e6a18e9fad8eb000296)
```
function howMuchILoveYou(nbPetals) {
  let phrases = ["I love you","a little","a lot","passionately","madly","not at all"];
return phrases [(nbPetals - 1) % phrases.length];
}
```

[Super Duper Easy](https://www.codewars.com/kata/55a5bfaa756cfede78000026/train/javascript/5e01a8890d5bc90032a407d5)
```javascript
function problem(x) {
  const res = x * 50 + 6;
  if (typeof (x) === 'string') return 'Error';
  else return res;
}
```

[Chuck Norris VII - True or False? (Beginner)](https://www.codewars.com/kata/570669d8cb7293a2d1001473/train/javascript/5e01aa3b2964c8002363e2e0)
```javascript
function ifChuckSaysSo() {
  return !true;
}
```

[Type of sum](https://www.codewars.com/kata/5a2e9ae2b6cfd7692a0000ba/train/javascript/5e01aadb5654a90014ff49e5)
```javascript
function typeOfSum(a, b) {
  sum = a + b;
  if (typeof sum === 'string') return 'string';
  else  return 'number';
}
```

[Convert a Number to a String!](https://www.codewars.com/kata//5265326f5fda8eb1160004c8)
```javascript
function numberToString(num) {
   return num.toString();
}
```

[Convert a String to a Number!](https://www.codewars.com/kata//544675c6f971f7399a000e79)
```javascript
var stringToNumber = function(str) { 
  return + str;
}
```

[Sum The Strings](https://www.codewars.com/kata//5966e33c4e686b508700002d)
```javascript
function sumStr(a,b) {
  const sumStr = +a + +b;
  if( a === '' && b === '') return '0';
  else
  return (sumStr + '');
}
```

[Convert a Boolean to a String](https://www.codewars.com/kata//551b4501ac0447318f0009cd)
```javascript
function booleanToString(b){
  if (b === true) return "true";
  else 
  return "false";
}
```

[Number toString](https://www.codewars.com/kata//53934feec44762736c00044b)
```javascript
let a = 123;
a = a + ''; 
console.log (a); 
```

[Discover The Original Price](https://www.codewars.com/kata//552564a82142d701f5001228)
```javascript
function discoverOriginalPrice(discountedPrice, salePercentage) {
  let retail = discountedPrice + (discountedPrice * salePercentage) / (100 - salePercentage);
  return Math.trunc(retail * 100) / 100; 
}
```

[Formatting decimal places #0](https://www.codewars.com/kata//5641a03210e973055a00000d)
```javascript
function twoDecimalPlaces(n) {
  return +n.toFixed(2);
}
```

[Area of a Square](https://www.codewars.com/kata//5748838ce2fab90b86001b1a)
```javascript
function squareArea(A) {
  return +((((A * 4) / Math.PI) / 2) ** 2).toFixed(2);
}
```

[Keep Hydrated!](https://www.codewars.com/kata//582cb0224e56e068d800003c)
```javascript
function litres(time) {
  return  Math.trunc(((500 / 60) * (time * 60))/1000);
}
```

[Century From Year](https://www.codewars.com/kata//5a3fe3dde1ce0e8ed6000097)
```javascript
function century(year) {
  if (year % 100 > 0) return Math.floor(year / 100) + 1;
  else return Math.floor(year / 100);
}
```

[Count Odd Numbers below n](https://www.codewars.com/kata//59342039eb450e39970000a6)
```javascript
function oddCount(n) {
  return  Math.floor(n / 2)
}
```

[How many times should I go?](https://www.codewars.com/kata//57efcb78e77282f4790003d8)
```javascript
function howManyTimes(annualPrice, individualPrice) {
  const visits = Math.ceil(annualPrice / individualPrice);
  return visits;
}
```
[Return the closest number multiple of 10](https://www.codewars.com/kata//58249d08b81f70a2fc0001a4)
```javascript
const closestMultiple10 = num => {
  if (num % 10 < 5)  return num - num % 10
  else if (num % 10 === 5) return num + num % 10;
  else return num + (10 - num % 10 );
};
```

[Keep up the hoop](https://www.codewars.com/kata//55cb632c1a5d7b3ad0000145)
```javascript
function hoopCount (n) {
  if (n > 0 && n < 10) return "Keep at it until you get it";
  else return "Great, now move on to tricks";
}
```

[Simple Comparison?](https://www.codewars.com/kata//57f6ecdfcca6e045d2001207)
```javascript
function add(a, b) {
  return (a == b) ? true : false;
}
```

[Is he gonna survive?](https://www.codewars.com/kata//59ca8246d751df55cc00014c)
```javascript
function hero(bullets, dragons) {
  let hero = (bullets / dragons >= 2) ? true : false;
  return hero;
}
```

[Even or Odd](https://www.codewars.com/kata//53da3dbb4a5168369a0000fe)
```javascript
function even_or_odd(number) {
  if (number % 2) return "Odd";
  else return "Even";
}
```