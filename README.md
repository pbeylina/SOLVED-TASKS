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

[Determine offspring sex based on genes XX and XY chromosomes
](https://www.codewars.com/kata//56530b444e831334c0000020)
```javascript
function chromosomeCheck(sperm) {
  if (sperm === 'XX') return "Congratulations! You're going to have a daughter.";
  else return "Congratulations! You're going to have a son.";
}
```

[What's the real floor?](https://www.codewars.com/kata//574b3b1599d8f897470018f6)
```javascript
function getRealFloor(n) {
  if (n <= 0) return n;
  else if (n === 15) return 13;
  else if (n > 15) return n -2;
  else return n -1;
}
```

[Calculate BMI](https://www.codewars.com/kata//57a429e253ba3381850000fb)
```javascript
function bmi(weight, height) {
 let b = weight/(height * height);
 if (b <= 18.5) return "Underweight";
   else if (b <= 25.0) return "Normal";
   else if (b <= 30.0) return "Overweight";
   else if (b > 30.0) return "Obese";
}
```

[Alan Partridge II - Apple Turnover](https://www.codewars.com/kata//580a094553bd9ec5d800007d)
```javascript
function apple(x) {
  if (Math.pow(x, 2) > 1000) return 'It\'s hotter than the sun!!';
  else return 'Help yourself to a honeycomb Yorkie for the glovebox.';
}
```

[Simple multiplication](https://www.codewars.com/kata//583710ccaa6717322c000105)
```javascript
function simpleMultiplication(number) {
  if (number % 2) return number * 9;
  else return number * 8;
}
```

[Sleigh Authentication](https://www.codewars.com/kata//52adc142b2651f25a8000643)
```javascript
function Sleigh() {}
  Sleigh.prototype.authenticate = function(name, password) {
  if (name === "Santa Claus" && password === "Ho Ho Ho!") return true;
  else return false;
  };
```

[Is n divisible by x and y?](https://www.codewars.com/kata//5545f109004975ea66000086)
```javascript
function isDivisible(n, x, y) {
  if (n % x === 0 && n % y === 0) return true;
  else return false;
}

```

[Is this a triangle?](https://www.codewars.com/kata//56606694ec01347ce800001b)
```javascript
function isTriangle(a, b, c) {
  if (a + b > c && b + c > a && a + c > b  )return true;
  else return false;
}
```

[Rock Paper Scissors!](https://www.codewars.com/kata//5672a98bdbdd995fad00000f)
```javascript
const rps = (p1, p2) => {
  if (p1 === 'scissors' && p2 === 'paper'|| p1 === 'rock' && p2 === 'scissors'|| p1 === 'paper' && p2 === 'rock');
  return 'Player 1 won!';
  else if (p1 === p2) return 'Draw!';
  else return 'Player 2 won!';
};
```
[L1: Set Alarm](https://www.codewars.com/kata//568dcc3c7f12767a62000038)
```javascript
function setAlarm(employed, vacation) {
  return (employed === true && vacation === false) ? true : false; 
}
```

[Can we divide it?](https://www.codewars.com/kata//5a2b703dc5e2845c0900005a)
```javascript
function isDivideBy(number, a, b) {
return (number % a === 0 && number % b === 0) ? true : false;
}
```

[Student's Final Grade](https://www.codewars.com/kata//5ad0d8356165e63c140014d4)
```javascript
function finalGrade (exam, projects) {
  if (exam > 90 || projects > 10) return 100;
  else if (exam > 75 && projects >= 5) return 90;
  else if (exam > 50 && projects >= 2) return 75;
  else return 0;
}
```

[Calculate Two People's Individual Ages](https://www.codewars.com/kata//58e0bd6a79716b7fcf0013b1)
```javascript
function getAges (sum, difference) {
let age1 = sum - (sum - difference) / 2;
let age2 = (sum - difference) / 2;
let ages1 = [age1, age2];
let ages2 = [age2, age1];
if (sum <= 0 || difference < 0 || age1 < 0 || age2 < 0) return null;
else if (age1 > age2 && age1 > 0 && age2 > 0 || sum === difference) return ages1;
else return ages2;
}
```

[Opposite number](https://www.codewars.com/kata//56dec885c54a926dcd001095)
```javascript
function opposite(number) {
  return -number;
}
```
[Convert boolean values to strings 'Yes' or 'No'.](https://www.codewars.com/kata//53369039d7ab3ac506000467)
```javascript
function boolToWord (bool) {
  return  bool === true ? "Yes" : "No";
}
```

[Be Concise I - The Ternary Operator](https://www.codewars.com/kata//56f3f6a82010832b02000f38)
```javascript
function describeAge (n) {
s="You\'re a(n) "
k=s+'kid'
t=s+'teenager'
a=s+'adult'
e=s+'elderly'
return n<13?k:n>12&n<18?t:n>16&n<65?a:e
}
```
[101 Dalmatians - squash the bugs, not the dogs!](https://www.codewars.com/kata//56f6919a6b88de18ff000b36)
```javascript
function howManyDalmatians (n) {
let dogs = ["Hardly any", "More than a handful!", "Woah that\'s a lot of dogs!", "101 DALMATIANS!!!"];  
return n < 11 ? dogs[0] : n > 10 & n < 51 ? dogs[1] : n > 50 & n < 101 ? dogs[2] : n === 101 ? dogs[3] : dogs[2];
}
```

[Do I get a bonus?](https://www.codewars.com/kata//56f6ad906b88de513f000d96)
```javascript
function bonusTime (salary, bonus) {
  return bonus === true ? "\u00A3" + salary * 10  : "\u00A3" + salary;
}
```

[Training JS #7: if..else and ternary operator](https://www.codewars.com/kata//57202aefe8d6c514300001fd)
```javascript
function saleHotdogs (n) {
  return n < 5 ? n * 100 : n >= 5 & n < 10 ? n * 95 : n * 90;
}
```

[Get Planet Name By ID](https://www.codewars.com/kata//515e188a311df01cba000003)
```javascript
function getPlanetName (id) {
  var name;
  switch(id) {
    case 1:
      name = 'Mercury'
      break;
    case 2:
      name = 'Venus'
      break;
    case 3:
      name = 'Earth'
      break;
    case 4:
      name = 'Mars'
      break;
    case 5:
      name = 'Jupiter'
      break;
    case 6:
      name = 'Saturn'
      break;
    case 7:
      name = 'Uranus'
      break;
    case 8:
      name = 'Neptune'
      break;    
  }  
  return name;
}
```