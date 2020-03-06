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
function opposite (number) {
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
[Basic Mathematical Operations](https://www.codewars.com/kata//57356c55867b9b7a60000bd7)
```javascript
function basicOp(o, v1, v2) {
  return o === '+' ? v1 + v2 : o === '-' ? v1 - v2 : o === '*' ? v1 * v2 : o === '/' ? v1 / v2 : false;
}
```

[Switch it Up!](https://www.codewars.com/kata//5808dcb8f0ed42ae34000031)
```javascript
function switchItUp (number) {
  switch (number) {
  case 0: return "Zero";
  case 1: return "One";
  case 2: return "Two";
  case 3: return "Three";
  case 4: return "Four";
  case 5: return "Five";
  case 6: return "Six"; 
  case 7: return "Seven";
  case 8: return "Eight";
  case 9: return "Nine";
  }
}
```

[simple calculator](https://www.codewars.com/kata//5810085c533d69f4980001cf)
```javascript
function calculator (a, b, sign) {
  switch (a, b, sign) {
  case a, b, "+" : return a + b;
  break;
  case a, b, "-" : return a - b;
  break;
  case a, b, "*" : return a * b;
  break;
  case a, b, "/" : return a / b;
  break;
  case a, b, " " : "unknown value";
  break;
  default : return "unknown value";
  break;
  }
}
```

[No zeros for heros](https://www.codewars.com/kata//570a6a46455d08ff8d001002)
```javascript
function noBoringZeros (n) {
  let i = 0;
  while (n % 10 === 0 && i <= 10) { 
   i++;
   n = n * 0.1;
  }
  return n;
}
```

[Power of two](https://www.codewars.com/kata//534d0a229345375d520006a0)
```javascript
function isPowerOfTwo (n) {
  let i = 1;
  while (n > 1) { 
  n = n / 2;
  }
  return n === 1;
}
```

[Powers of 3](https://www.codewars.com/kata//57be674b93687de78c0001d9)
```javascript
function largestPower (n) {
  let k = 0;
  while (Math.pow(3, k) < n) {
  ++k;
  }
  return Math.max(k) - 1; 
}
```

[Difference Of Squares](https://www.codewars.com/kata//558f9f51e85b46e9fa000025)
```javascript
function differenceOfSquares (n) {
  let sum1 = 0;
  let sum2 = 0;
  for (let i = 1; i <= n; ++i) {
  sum1 += i;
  sum2 += Math.pow(i, 2)
  }
  {
  sum1 = Math.pow(sum1, 2);
  return sum1 - sum2;
  }
}
```

[Factorial](https://www.codewars.com/kata//57a049e253ba33ac5e000212)
```javascript
function factorial (n) {
  f = 1; i = 1;
  while ( i <= n) {
  f *= i;
  i++;
  }
  return f;
}
```


[The wheat/rice and chessboard problem](https://www.codewars.com/kata//5b0d67c1cb35dfa10b0022c7)
```javascript
function squaresNeeded (grains) {
  let g = 1; square = 1 ; s = 0;
  while (s < grains) {
  s += g;
  g *= 2;
  ++square;
  }
  return square - 1;
}
```

[Grasshopper - Summation](https://www.codewars.com/kata//55d24f55d7dd296eb9000030)
```javascript
var summation = function(num){
  let sum = 0;
  for (let i = 0; i <= num; ++i) {
    sum += i;
  }
  return sum;
}
```

[Sum of Multiples](https://www.codewars.com/kata//57241e0f440cd279b5000829)
```javascript
function sumMul(n, m){
  let sum = 0;
  for (let i = n; i < m; i += n){
    sum += i; 
  } 
  return (sum > 0 && m > 0) ? sum : 'INVALID';
}
```

[Draw stairs](https://www.codewars.com/kata//5b4e779c578c6a898e0005c5)
```javascript
function drawStairs(n){
  let s = '';
  for (let i = 0; i < n; i++) {
    s += ' '.repeat(i) + 'I';
    if (i < n - 1) {
      s += '\n';
    }
  }
  return s;
}
```

[Sum of the first nth term of Series](https://www.codewars.com/kata//555eded1ad94b00403000071)
```javascript
function SeriesSum(n){
  let sum = 0;
  for (i = 0; i < n; i++) {
    sum += 1 / (1 + i * 3);
  }
  return sum.toFixed(2)
}
```

[Beginner Series #3 Sum of Numbers](https://www.codewars.com/kata//55f2b110f61eb01779000053)
```javascript
function getSum(a, b){
  let sum = 0;
  for (i = Math.min(a, b); i <= Math.max(a, b); i++) {
    sum += i;
  }
  return sum;
}
```

[Power](https://www.codewars.com/kata//562926c855ca9fdc4800005b)
```javascript
function numberToPower(n, p){
  let res = 1;
  for (let i = 1; i <= p; i++) {
    res = res * n;
  } 
  return res;
}
```

[isReallyNaN](https://www.codewars.com/kata//56c24c58e0c0f741d4001aef)
```javascript
const isReallyNaN = (val) => {
  return (Number.isNaN(val)) ? true : false;
}
```

[Filter the number](https://www.codewars.com/kata//55b051fac50a3292a9000025)
```javascript
FilterString = function(value){
  let num = '';
  for (let i = 0; i < value.length; i++) {
    if (isNaN (value[i]) === false) 
    num += value[i];
  }
  return +num; 
}
```

[Is integer safe to use?](https://www.codewars.com/kata//55a4f9afeffe4231090000d6)
```javascript
function SafeInteger(n){
  return Number.isSafeInteger(n) ? true : false;
}
```

[Return Negative](https://www.codewars.com/kata//55685cd7ad70877c23000102)
```javascript
function makeNegative(num){
  return num > 0 ? -num : num;
}
```

[Invert values](https://www.codewars.com/kata//5899dc03bc95b1bf1b0000ad)
```javascript
function invert(array){
  return array.map(item => item * - 1);
}
```

[BASIC: Making Six Toast.](https://www.codewars.com/kata//5834fec22fb0ba7d080000e8)
```javascript
function sixToast(num){
  let pc = 6;
  return Math.abs(num - pc);
}
```

[Closest elevator](https://www.codewars.com/kata//5c374b346a5d0f77af500a5a)
```javascript
function elevator(l, r, c) {
  let difL = Math.abs(c - l);
  let difR = Math.abs(c - r);
  let difE = Math.abs(r - l); 
  return (c === r & l === r & difL === difR) ? 'right': (c < r & r < l)? 'right': (c === l & c > difL)? 'left': (c > l & l > r)? 'left': (c < difL  & c > difE) ? 'left': (c < difR & c <difE) ? 'left':'right'; 
}
```

[To square(root) or not to square(root)](https://www.codewars.com/kata//57f6ad55cca6e045d2000627)
```javascript
function squareOrSquareRoot(array) {
  let res = [];  
  for (let i = 0; i < array.length; ++i) {
    if (Math.sqrt(array[i]) % 1 === 0) res.push (Math.sqrt(array[i]));
    else res.push (Math.pow(array[i], 2))
  }
  return res;
}
```

[Square Every Digit](https://www.codewars.com/kata//546e2562b03326a88e000020)
```javascript
function squareDigits(num) {
  let res = num.toString().split('').map(Number);
  let sd =[];
  for (let i = 0; i < res.length; i++) {
    sd.push (Math.pow(res[i], 2));
  }
  return +sd.join('')
}
```

[Squares sequence](https://www.codewars.com/kata//5546180ca783b6d2d5000062)
```javascript
function squares(x, n) {
  if (n <= 0) return [];
  let s = [x];
  let b = x;
  while (s.length <= n - 1) {
    x++;
    s.push (b *= b);
  }
  return s
}
```

[You're a square!](https://www.codewars.com/kata//54c27a33fb7da0db0100040e)
```javascript
var isSquare = function(n) {
  return (Number.isInteger(Math.sqrt(n)))? true : false; 
}
```

[Find the next perfect square!](https://www.codewars.com/kata//56269eb78ad2e4ced1000013)
```javascript
function findNextSquare(sq) {
  return (Number.isInteger(Math.sqrt(sq))) ? Math.pow(1 + (Math.sqrt(sq)), 2) : -1;
}
```

[Beginner Series #4 Cockroach](https://www.codewars.com/kata//55fab1ffda3e2e44f00000c6)
```javascript
function cockroachSpeed(s) {
  return Math.floor(s * 100000 / 3600);
}
```

[Price of Mangoes](https://www.codewars.com/kata//57a77726bb9944d000000b06)
```javascript
function mango(qty, price) {
  return (qty - Math.floor(qty / 3)) * price;
}
```

[Holiday VIII - Duty Free](https://www.codewars.com/kata//57e92e91b63b6cbac20001e5)
```javascript
function dutyFree(n, d, h) {
  return Math.floor(h / ((n / 100) * d));
}
```

[All Star Code Challenge #22](https://www.codewars.com/kata//5865cff66b5699883f0001aa)
```javascript
function toTime(sec) {
  let h = Math.trunc(sec / 3600);
  let m = Math.floor((sec / 3600 - h) * 60);
  let str = `${h} hour(s) and ${m} minute(s)`;
  return str;
}
```

[Formatting decimal places #1](https://www.codewars.com/kata//5641c3f809bf31f008000042)
```javascript
function twoDecimalPlaces(number) {
  return ((parseInt(number * 100)) / 100);
 }
```

[Tortoise racing](https://www.codewars.com/kata//55e2adece53b4cdcb900006c)
```javascript
function race(v1, v2, g) {
  if (v1 >= v2) return null;
  let t = g / (v2 - v1);
  let tSec = t * 3600;
  let h = Math.trunc(tSec / 3600);
  let m = Math.trunc((tSec - h * 3600) / 60);
  let s = Math.trunc(tSec- h * 3600 - m * 60);
  return [h, m, s];
}
```

[Lario and Muigi Pipe Problem](https://www.codewars.com/kata//56b29582461215098d00000f)
```javascript
function pipeFix(numbers) {
  let arr = [];
  for (let i = Math.min(...numbers); i <= Math.max(...numbers); i++) {
  arr.push (i);
  }
  return arr;
}
```

[Expressions Matter](https://www.codewars.com/kata//5ae62fcf252e66d44d00008e)
```javascript
function expressionMatter(a, b, c) {
  return Math.max((a + b) * c, a * b + c, a + b + c, (a * b) * c, a * (b + c));
}
```

[Convert to Binary](https://www.codewars.com/kata//59fca81a5712f9fa4700159a)
```javascript
function toBinary(n) {
  return +n.toString(2);
}
```

[Binary Addition](https://www.codewars.com/kata//551f37452ff852b7bd000139)
```javascript
function addBinary(a, b) {
  return (a + b).toString(2);
}
```

[Calculate Price Excluding VAT](https://www.codewars.com/kata/5890d8bc9f0f422cf200006b)
```javascript
const excludingVatPrice = price => price === null ? -1 : +(price / 1.15).toFixed(2);
```

[Parse nice int from char problem](https://www.codewars.com/kata/557cd6882bfa3c8a9f0000c1)
```javascript
function getAge(inputString) {
  return  parseInt(inputString);
}
```

[Hex to Decimal](https://www.codewars.com/kata/57a4d500e298a7952100035d)
```javascript
function hexToDec(hexString) {
  return  parseInt(hexString, 16);
}
```

[Bin to Decimal](https://www.codewars.com/kata/57a5c31ce298a7e6b7000334)
```javascript
const binToDec = bin => Number.parseInt(bin.toString(2), 2);
```

[Parse float](https://www.codewars.com/kata/57a386117cb1f31890000039)
```javascript
const parseF = s => Number.isNaN(Number.parseFloat(s)) ? null : parseFloat(s);
```

[Sum Arrays](https://www.codewars.com/kata//53dc54212259ed3d4f00071c)
```javascript
function sum(numbers) {
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
    return sum ;  
}
```

[Count the Monkeys!](https://www.codewars.com/kata//56f69d9f9400f508fb000ba7)
```javascript
function monkeyCount(n) {
  let quantity = [];
  for (let i = 1; i <= n; i++) {
    quantity.push (i);
  }
  return quantity;
}
```

[Filling an array (part 1)](https://www.codewars.com/kata//571d42206414b103dc0006a1)
```javascript
function arr(N) {
  let res = [];
  for (let i = 0; i <= N - 1; i++) {
    res.push (i);
  }
    return res;
}
```

[What is type of variable?](https://www.codewars.com/kata//57293671c98f77e84b000065)
```javascript
function type(value) {
  return ({}.toString.call(value) === '[object Date]') ? 'date' : 
  (Array.isArray(value) === true) ? 'array' : 
  ({}.toString.call(value) === '[object Null]') ? 'null' : typeof(value);
}
```

[Is every value in the array an array?](https://www.codewars.com/kata//582c81d982a0a65424000201)
```javascript
const arrCheck = value => value.every(Array.isArray);
```

[Enumerable Magic #3 - Does My List Include This?](https://www.codewars.com/kata//545991b4cbae2a5fda000158)
```javascript
function include(arr, item) {
  return arr.includes(item, item.every < arr.length);
}
```

[Difference of Volumes of Cuboids](https://www.codewars.com/kata//58cb43f4256836ed95000f97)
```javascript
function findDifference(a, b) {
  return Math.abs(a[0] * a[1] * a[2] - b[0] * b[1] * b[2]);
}
```
