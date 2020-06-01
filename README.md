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

[Counting sheep...](https://www.codewars.com/kata//54edbc7200b811e956000556)
```javascript
function countSheeps(arrayOfSheep) {
  let sum = arrayOfSheep.filter( i => i === true);
  return sum.length;
}
```

[A Needle in the Haystack](https://www.codewars.com/kata//56676e8fabd2d1ff3000000c)
```javascript
function findNeedle(haystack) {
  let str = 'found the needle at position ';
  return str + `${haystack.indexOf ('needle', 0)}`;
}
```

[Total amount of points](https://www.codewars.com/kata//5bb904724c47249b10000131)
```javascript
function points(games) {
  let sum = 0;
  games.forEach((el) => (el[0] > el[2]) ? sum += 3 : (el[0] === el[2]) ? sum += 1 : 0);
  return sum;
}
```

[Calculate average](https://www.codewars.com/kata//57a2013acf1fa5bfc4000921)
```javascript
function find_average(array) {
  return array.reduce((a, b) => (a + b)) / array.length;
}
```

[Square(n) Sum](https://www.codewars.com/kata//515e271a311df0350d00000f)
```javascript
function squareSum(num) {
  return num.reduce((a, num) => a + Math.pow(num, 2), 0);
}
```

[Find the first non-consecutive number](https://www.codewars.com/kata//58f8a3a27a5c28d92e000144)
```javascript
function firstNonConsecutive(arr) {
  for (let i = 0; i < arr.length - 1; i++) {
    if (arr[i + 1] !== arr[i] + 1)
    return arr[i + 1];
  }
    return null;
}
```

[How good are you really?](https://www.codewars.com/kata//5601409514fc93442500010b)
```javascript
function betterThanAverage(classPoints, yourPoints) {
  return classPoints.reduce((a, b) => a + b) / classPoints.length < yourPoints;
}
```

[Sum of positive](https://www.codewars.com/kata//5715eaedb436cf5606000381)
```javascript
function positiveSum(arr) {
  return arr.reduce((sum, arr) => arr > 0 ? sum + arr : sum, 0);
}
```

[Odd or Even?](https://www.codewars.com/kata//5949481f86420f59480000e7)
```javascript
function oddOrEven(arr) {
  let sum = 0;
  for (let i = 0; i < arr.length; i++) {
    if (sum.length == 0) {
    return 'even';
    }
    else  sum += arr[i];
  }
  return sum % 2 === 0 ? 'even' : 'odd';
}
```

[Count of positives / sum of negatives](https://www.codewars.com/kata//576bb71bbbcf0951d5000044)
```javascript
function countPositivesSumNegatives(input) {
  if (!input || input.length == 0) return [];
  let count = 0;
  let sum = 0;
  input.forEach (el => {
    if (el > 0) {
    count++;
    } else {
    sum += el;
    }
  });
  return [count, sum];
}
```

[Divide and Conquer](https://www.codewars.com/kata//57eaec5608fed543d6000021)
```javascript
function divCon(x) {
  let sumNum = 0;
  let sumStr = 0;
  for (let i = 0; i <= x.length; i++) {
    if (typeof x[i] === 'number') {
    sumNum += x[i];
    }
    else if (typeof x[i] === 'string') {
    sumStr += +x[i];
    }
  }
  return sumNum - sumStr;
}
```

[Sum of Odd Cubed Numbers](https://www.codewars.com/kata//580dda86c40fa6c45f00028a)
```javascript
function cubeOdd(arr) {
let count = 0; 
  for (let i = 0; i < arr.length; i++) {
    if (isNaN(arr[i])) {
    return undefined;
    }
    else if (arr[i] % 2 !== 0) {
    count += Math.pow((arr[i]), 3);
    }
  }
  return count;
}
```

[Find the smallest integer in the array](https://www.codewars.com/kata//55a2d7ebe362935a210000b2)
```javascript
class SmallestIntegerFinder {
  findSmallestInt(args) {
  return Math.min(...args)
  }
}
```

[Sum without highest and lowest number](https://www.codewars.com/kata//576b93db1129fcf2200001e6)
```javascript
function sumArray(arr) {
  if (!arr || arr.length < 2) return 0;
  let min = arr [0];
  let max = arr [0];
  let sum = arr [0];
  for (let i = 1; i < arr.length; i++) {
    if (arr[i] < min) min = arr[i];
    if (arr[i] > max) max = arr[i];
      sum += arr[i];
  }
  return sum - min - max;
}
```

[Remove the minimum](https://www.codewars.com/kata//563cf89eb4747c5fb100001b)
```javascript
function removeSmallest(num) {
  if (!num) return [];
  let res = [...num];
  let min = Math.min.apply(null, res);
  res.splice(res.indexOf(min), 1);
  return res;
}
```

[Find Maximum and Minimum Values of a List](https://www.codewars.com/kata//577a98a6ae28071780000989)
```javascript
let min = function(list) {
  let min = list[0];
  for (let i = 1; i < list.length; i++) {
    if (list[i] < min) min = list[i];
  }
  return min;
}

let max = function(list) {
  let max = list[0]; 
  for (let i = 0; i < list.length; i++) { 
    if (max < list[i]) max = list[i]; 
  }
  return max;
}
```

[Find Maximum and Minimum Values of a List](https://www.codewars.com/kata//577a98a6ae28071780000989)
```javascript
const min = list => Math.min(...list);
const max = list => Math.max(...list);
```

[Count by X](https://www.codewars.com/kata//5513795bd3fafb56c200049e)
```javascript
function countBy(x, n) {
  let z = [];
  for (let i =1; i <= n; i ++) {
  z.push(x * i)
  }
  return z;
}
```

[Unfinished Loop - Bug Fixing #1](https://www.codewars.com/kata//55c28f7304e3eaebef0000da)
```javascript
function createArray(number) {
  var newArray = [];
  for(var counter = 1; counter <= number; counter++) {
    newArray.push(counter);
  }
  return newArray;
}
```

[Generate range of integers](https://www.codewars.com/kata//55eca815d0d20962e1000106)
```javascript
function generateRange(min, max, step) {
  let range = [];
  let count = 0;
  for (let i = min; count <= max - step; i = step) {
    range.push(count += i);
  }
  return range;
}
```

[Training JS #10: loop statement --for](https://www.codewars.com/kata//5721a78c283129e416000999)
```javascript
function pickIt(arr) {
  let odd = []; 
  let even = [];
  for(let i = 0; i < arr.length; i++) {
    if (arr[i] % 2) odd.push(arr[i]);
    else even.push(arr[i]);
  }
  return [odd, even];
}
```

[Powers of 2](https://www.codewars.com/kata//57a083a57cb1f31db7000028)
```javascript
function powersOfTwo(n) {
  let res = [];
  for(let i = 0; i <= n; i++) {
    res.push(Math.pow(2, i))
  }
  return res;
}
```

[Reversed sequence](https://www.codewars.com/kata//5a00e05cc374cb34d100000d)
```javascript
function reverseSeq(n) {
  let res = [];
  for (let i = n; i > 0; i--) {
    res.push(i);
  }
  return res;
}
```

[Find the divisors!](https://www.codewars.com/kata//544aed4c4a30184e960010f4)
```javascript
function divisors(integer) {
  let res = [];
  for (let i = 2; i < integer; i++) 
    if (integer % i === 0) res.push(i); 
  return (res.length === 0) ? integer + ' is prime' : res;
}
```

[Pre-FizzBuzz Workout #1](https://www.codewars.com/kata//569e09850a8e371ab200000b)
```javascript
function preFizz(n) {
  let res = [];
  for (let i = 1; i <= n; i++ ) {
    res.push(i);
  }
  return res;
}
```

[Training JS #4: Basic data types--Array](https://www.codewars.com/kata//571effabb625ed9b0600107a)
```javascript
function getLength(arr) {
  return  arr.length;
}

function getFirst(arr) {
  return arr[0];
}

function getLast(arr) {
  return arr[arr.length-1]
}

function pushElement(arr) {
  let el = 1;
  arr.push(el);
  return arr;
}

function popElement(arr) {
  arr.pop();
  return arr;
}
```

[No Loops 2 - You only need one](https://www.codewars.com/kata//57cc40b2f8392dbf2a0003ce)
```javascript
function check(a, x) {
return a.includes(x) ? true : false;
}
```
[You only need one - Beginner](https://www.codewars.com/kata//57cc975ed542d3148f00015b)
```javascript
const check = (a, x) => a.includes(x) ? true : false;
```
[Be Concise IV - Index of an element in an array](https://www.codewars.com/kata//5703c093022cd1aae90012c9)
```javascript
let find = (arr, el) => arr.indexOf(el) === 0 ? 0 : arr.indexOf(el) > 0 ? arr.indexOf(el) : "Not found";
```

[A wolf in sheep's clothing](https://www.codewars.com/kata//5c8bfa44b9d1192e1ebd3d15)
```javascript
function warnTheSheep(queue) {
  let l = queue.length;
  let wolf = queue.indexOf('wolf');
  return (l === wolf + 1) ? "Pls go away and stop eating my sheep":
 `Oi! Sheep number ${l - 1 - wolf}! You are about to be eaten by a wolf!`
}
```

[Find numbers which are divisible by given number](https://www.codewars.com/kata//55edaba99da3a9c84000003b)
```javascript
function divisibleBy (numbers, divisor){
  return numbers.filter((el) => el % divisor === 0);
}
```

[Removing Elements](https://www.codewars.com/kata//5769b3802ae6f8e4890009d2)
```javascript
function removeEveryOther(arr) {
  return arr.filter((el, i) => i % 2 !==1); 
}
```

[Well of Ideas - Easy Version](https://www.codewars.com/kata//57f222ce69e09c3630000212)
```javascript
function well(x) {
  let res = x.filter(el => el === 'good');
  return res.length < 1 ? 'Fail!' : res.length <= 2 ? 'Publish!' : 'I smell a series!';
}
```

[JavaScript Array Filter](https://www.codewars.com/kata//514a6336889283a3d2000001)
```javascript
function getEvenNumbers(numbersArray) {
  return numbersArray.filter(el => el % 2 === 0);
}
```

[filterEvenLengthWords](https://www.codewars.com/kata//59564f3bcc15b5591a00004a)
```javascript
function filterEvenLengthWords(words) {
  return words.filter(el => el.length % 2 === 0);
}
```

[Find how many times did a team from a given country win the Champions League?](https://www.codewars.com/kata//581b30af1ef8ee6aea0015b9)
```javascript
const countWins = (winnerList, country) => winnerList.filter(el => el.country === country).length; 
```

[Array.diff](https://www.codewars.com/kata//523f5d21c841566fde000009)
```javascript
const array_diff = (a, b) => a.filter(el => !b.includes(el));
```

[Find Duplicates](https://www.codewars.com/kata//5558cc216a7a231ac9000022)
```javascript
function duplicates(arr) {
  return arr.filter((el, i) => i !== arr.indexOf(el) && i === arr.lastIndexOf(el));
}
```

[Train to remove duplicates from an array with filter()](https://www.codewars.com/kata//58308360aeb69a460b0002b2)
```javascript
function unique(arr) {
  return arr.filter((el, i) => i === arr.indexOf(el));
}
```

[Santa's Naughty List](https://www.codewars.com/kata//5a0b4dc2ffe75f72f70000ef)
```javascript
function findChildren(santasList, children) {
  return [...new Set(children.filter(name => santasList.includes(name)).sort())];
}
```

[Convert number to reversed array of digits](https://www.codewars.com/kata//5583090cbe83f4fd8c000051)
```javascript
const fixTheMeerkat = arr => arr.reverse();
```

[My head is at the wrong end!](https://www.codewars.com/kata//56f699cd9400f5b7d8000b55)
```javascript
function sumOfDifferences(arr) {
  return arr.sort((a, b) => b - a)
  .reduce((a, el, i, arr) => i + 1 < arr.length ? a + el - arr[i + 1] : a, 0)
}
```

[Sum of differences in array](https://www.codewars.com/kata//5b73fe9fb3d9776fbf00009e)
```javascript
function sumOfDifferences(arr) {
  return arr.sort((a, b) => b - a)
  .reduce((a, el, i, arr) => i + 1 < arr.length ? a + el - arr[i + 1] : a, 0)
}
```

[Sum of two lowest positive integers](https://www.codewars.com/kata//558fc85d8fd1938afb000014)
```javascript
function sumTwoSmallestNumbers(num) {  
  num.sort((a, b) => a - b);
  return num[0] + num[1];
}
```

[Two Oldest Ages](https://www.codewars.com/kata//511f11d355fe575d2c000001)
```javascript
const twoOldestAges = ages => ages.sort((a, b) => a - b).slice(-2);
```

[Sentence Smash](https://www.codewars.com/kata//53dc23c68a0c93699800041d)
```javascript
const smash = words => words.join(' ');
```

[String Templates - Bug Fixing #5](https://www.codewars.com/kata//55c90cad4b0fe31a7200001f)
```javascript
function buildString(...template) {
  return `I like ${template.join(', ')}!`;
}
```

[Printing Array elements with Comma delimiters](https://www.codewars.com/kata//56e2f59fb2ed128081001328)
```javascript
const printArray = array => array.join();
```

[CSV representation of array](https://www.codewars.com/kata//5a34af40e1ce0eb1f5000036)
```javascript
function toCsvText(array) {
  return array.join('\n'); 
}
```

[Enumerable Magic #1 - True for All?](https://www.codewars.com/kata//54598d1fcbae2ae05200112c)
```javascript
function all (arr, fun) {
  return arr.every(fun);
}
```

[Grasshopper - Array Mean](https://www.codewars.com/kata//55d277882e139d0b6000005d)
```javascript
const findAverage = nums => nums.reduce((a, el) => a + el) / nums.length;
```

[Array plus array](https://www.codewars.com/kata//5a2be17aee1aaefe2a000151)
```javascript
const arrayPlusArray = (arr1, arr2) => arr1.concat(arr2).reduce((a, el) => a + el);
```

[Beginner - Reduce but Grow](https://www.codewars.com/kata//57f780909f7e8e3183000078)
```javascript
const grow = x => x.reduce((a, el) => a * el, 1);
```

[SpeedCode #2 - Array Madness](https://www.codewars.com/kata//56ff6a70e1a63ccdfa0001b1)
```javascript
function arrayMadness (a, b) {
  return a.reduce((a, el) => a + Math.pow(el, 2), 0) > b.reduce((a, el) => a + Math.pow(el, 3), 0);
}
```

[Beginner - Lost Without a Map](https://www.codewars.com/kata//57f781872e3d8ca2a000007e)
```javascript
const maps = x => x.map(el => el * 2);
```

[Enumerable Magic #25 - Take the First N Elements](https://www.codewars.com/kata//545afd0761aa4c3055001386)
```javascript
const take = (arr, n) => arr.splice(0, n);
```

[Remove First and Last Character Part Two](https://www.codewars.com/kata//570597e258b58f6edc00230d)
```javascript
function array(arr) {
  return arr.split(',').slice(1, -1).join(' ') || null;
}
```

[Jenny's secret message](https://www.codewars.com/kata//55225023e1be1ec8bc000390)
```javascript
function greet(name) {
  if(name === "Johnny") return "Hello, my love!";
  return `Hello, ${name}!`;
}
```

[Template Strings](https://www.codewars.com/kata//55a14f75ceda999ced000048)
```javascript
let TempleStrings = (obj, feature) => `${obj} are ${feature}`;
```

[Returning Strings](https://www.codewars.com/kata//55a70521798b14d4750000a4)
```javascript
function greet(name) {
  return `Hello, ${name} how are you doing today?`;
}
```

[Grasshopper - Combine strings](https://www.codewars.com/kata//55f73f66d160f1f1db000059)
```javascript
let combineNames = (first, last) => `${first} ${last}`;
```

[Grasshopper - Debug sayHello](https://www.codewars.com/kata//5625618b1fe21ab49f00001f)
```javascript
function sayHello(name) {
  return `Hello, ${name}`;
}
```

[If you can't sleep, just count sheep!!](https://www.codewars.com/kata//5b077ebdaf15be5c7f000077)
```javascript
var countSheep = function (num) {
  let str = ' sheep...';
  let res = '';
  for (let i = 1; i <= num; i++) {
    res += i + str;
  }
  return res;
}
```

[get character from ASCII Value](https://www.codewars.com/kata//55ad04714f0b468e8200001c)
```javascript
const getChar = c => String.fromCharCode(c);
```

[Is this my tail?](https://www.codewars.com/kata//56f695399400f5d9ef000af5)
```javascript
function correctTail(body, tail) {
  sub = body[body.length-1];
  if (sub === tail) {
    return true;
  }
  else 
    return false;
  }
```

[Abbreviate a Two Word Name](https://www.codewars.com/kata//57eadb7ecd143f4c9c0000a3)
```javascript
function abbrevName (name) { 
  let space = name.indexOf(' ', 0)
  return (name[0] + '.' + name[space + 1]).toUpperCase();
}
```

[5 without numbers !!](https://www.codewars.com/kata//59441520102eaa25260000bf)
```javascript
function unusualFive(x) {
  x = 'world';
  return x.length;  
}
```

[Regex validate PIN code](https://www.codewars.com/kata//55f8a9c06c018a0d6e000132)
```javascript
const validatePIN = pin => /^(\d{4}|\d{6})$/.test(pin) ? true : false;
```

[Numbers to Letters](https://www.codewars.com/kata//57ebaa8f7b45ef590c00000c)
```javascript
function switcher (x) {
  let res = '';
  let str = "0zyxwvutsrqponmlkjihgfedcba!? ";
  for (let i = 0; i < x.length; i++) {
    res += str[x[i]];
  }
  return res;
}
```

[Remove First and Last Character](https://www.codewars.com/kata//56bc28ad5bdaeb48760009b0)
```javascript
function removeChar(str) {
  return str.slice(1, -1);
}
```

[Regex count lowercase letters](https://www.codewars.com/kata//56a946cd7bd95ccab2000055)
```javascript
const lowercaseCount = str => str.replace(/[^a-z]/g, '').length;
```

[Double Char](https://www.codewars.com/kata//56b1f01c247c01db92000076)
```javascript
function doubleChar(str) {
  let myStr = '';
  for (let i = 0; i < str.length; i++) {
    myStr += str[i] + str[i];
  }
  return myStr;
}
```

[Remove String Spaces](https://www.codewars.com/kata//57eae20f5500ad98e50002c5)
```javascript
const noSpace = x => x.replace(/\s+/g, '');
```

[Remove String Spaces](https://www.codewars.com/kata//57eae20f5500ad98e50002c5)
```javascript
function noSpace(x) {
  let myStr = '';
  for (let i = 0; i < x.length; i++) {
    if (x[i] !== ' ') 
    myStr += x[i];
  }
  return myStr;
}
```

[Spacify](https://www.codewars.com/kata//57f8ee485cae443c4d000127)
```javascript
function spacify(str) {
  let myStr = '';
  for (let i = 0; i < str.length; i++) {
    myStr += str[i] + ' ';
  }
  return myStr.trim();
}
```

[Unique In Order](https://www.codewars.com/kata//54e6533c92449cc251001667)
```javascript
function tripleTrouble(one, two, three) {
  let myStr = '';
  for (let i = 0; i < one.length; i++) {   
    myStr = myStr + one[i] + two[i] + three[i];
  }
  return myStr;
}
```

[Unique In Order](https://www.codewars.com/kata//54e6533c92449cc251001667)
```javascript
var uniqueInOrder = function(str) {
  let arr = [];
  if (!str) return []; else arr.push(str[0]);
  for (let i = 1; i < str.length; i++) {
    if (str[i] !== str[i - 1]) arr.push(str[i]);
  }
  return arr;
}
```

[Reversed Strings](https://www.codewars.com/kata//5168bb5dfe9a00b126000018)
```javascript
function solution(str) {
  let myStr = '';
  for (let i = str.length - 1; i >= 0; i--) {
    myStr += str[i];
  }
  return myStr;
}
```

[Is it a palindrome?](https://www.codewars.com/kata//57a1fd2ce298a731b20006a4)
```javascript
function isPalindrome(x) {
  let str = x.toLowerCase();
  return str === str.split('').reverse().join(''); 
}
```

[The Wide-Mouthed frog!](https://www.codewars.com/kata//57ec8bd8f670e9a47a000f89)
```javascript
function mouthSize(animal) {
  return animal.toLowerCase() === 'alligator' ? "small" : "wide";
}
```

[MakeUpperCase](https://www.codewars.com/kata//57a0556c7cb1f31ab3000ad7)
```javascript
const makeUpperCase = str => str.toUpperCase();
```

[Capitalization and Mutability](https://www.codewars.com/kata//595970246c9b8fa0a8000086)
```javascript
function capitalizeWord(word) {
  return word[0].toUpperCase() + word.slice(1);
}
```

[Find the capitals](https://www.codewars.com/kata//539ee3b6757843632d00026b)
```javascript
function capitals(word) {
  let res = [];
  for (let i = 0; i < word.length; i++) {
    if (word[i] === word[i].toUpperCase()) 
      res.push(i)
    }
    return res;
  }
```

[Mumbling](https://www.codewars.com/kata//5667e8f4e3f572a8f2000039)
```javascript
function accum(s) {
  return s.split('').map((x, index) => x.toUpperCase() + Array(index + 1).join(x.toLowerCase())).join('-');
}
```

[Thinking & Testing : Something capitalized](https://www.codewars.com/kata//56d93f249c844788bc000002)
```javascript
function testit(s) {  
  if (s === '') return s;
  let str = s.split(' ');
  return str.map(el => el.slice(0, el.length - 1) + el[el.length - 1].toUpperCase()).join(' ');    
}
```

[Miles per gallon to kilometers per liter](https://www.codewars.com/kata//557b5e0bddf29d861400005d)
```javascript
function converter (mpg) {
  let gal = 4.54609188;
  let mi = 1.609344;
  return +((mpg * mi) / gal).toFixed(2);
}
```

[Find the Slope](https://www.codewars.com/kata//55a75e2d0803fea18f00009d)
```javascript
function slope(points) {
  let a = points[0];
  let b = points[1];
  let c = points[2];
  let d = points[3];
  if (a === c) {
  return 'undefined';
  }
  return ((d - b) / (c - a)).toString();
}
```

[Training JS #21: Methods of String object--trim() and the string template](https://www.codewars.com/kata//5729b103dd8bac11a900119e)
```javascript
function fiveLine(s) {
  let str = s.trim();
  let res = '';
  for (let i = 1; i <= 5; i++) {
    if (i === 5) res += `${str.repeat(i)}`;
      else res += `${str.repeat(i)}\n`;
  }
  return res;
}
```

[repeatIt](https://www.codewars.com/kata//557af9418895e44de7000053)
```javascript
const repeatIt = (str, n) => typeof str === 'string' ? str.repeat(n) : 'Not a string';
```

[String repeat](https://www.codewars.com/kata//57a0e5c372292dd76d000d7e)
```javascript
function repeatStr (n, s) {
  return s.repeat(n);
}
```

[Name on billboard](https://www.codewars.com/kata//570e8ec4127ad143660001fd)
```javascript
function billboard(name, price = 30) {
  let res = 0;
  for (let i = 0; i < name.length; i++) {
    res += price;
  }
  return res;
}
```

[Do you speak "English"?](https://www.codewars.com/kata//58dbdccee5ee8fa2f9000058)
```javascript
const spEng = sentence => sentence.toLowerCase().includes('english') ? true : false;
```

[Mispelled word](https://www.codewars.com/kata//5892595f190ca40ad0000095)
```javascript
function  mispelled(word1, word2) {
let count = 0;
if (word1.length === word2.length) { 
  for (let i = 0; i <= word1.length; i++) {
    if (word1[i] !== word2[i]) count++;
  } 
    if (count <= 1 ) return true;
    return false;
} else 
if (word1.length === word2.length + 1)
return word1.includes(word2);
else if (word1.length + 1 === word2.length)
return word2.includes(word1);
else return false;
}
```

[Don't give me five!](https://www.codewars.com/kata//5813d19765d81c592200001a)
```javascript
function dontGiveMeFive(start, end) {
  let count = 0;
  let str;
  for (let i = start; i <= end; i++){
    str = i + '';
    if (!(str.includes('5'))) count++;
   }
   return count;
}
```

[Find the position!](https://www.codewars.com/kata//5808e2006b65bff35500008f)
```javascript
function position(letter) {
  let str = 'abcdefghijklmnopqrstuvwxyz';
  return `Position of alphabet: ${str.padStart(27).indexOf(letter)}`;
}
```

[Training JS #17: Methods of String object--indexOf(), lastIndexOf() and search()](https://www.codewars.com/kata//57277a31e5e51450a4000010)
```javascript
const firstToLast = (str, c) => str.search(c) === -1 ? -1: 
str.indexOf(c) === str.lastIndexOf(c) ? 0 : str.lastIndexOf(c) - str.indexOf(c);
```

[validate code with simple regex](https://www.codewars.com/kata//56a25ba95df27b7743000016)
```javascript
const validateCode = code => /^[1-3]/.test(code) ? true : false;
```

[String ends with?](https://www.codewars.com/kata//51f2d1cafc9c0f745c00037d)
```javascript
const solution = (str, ending) => str.endsWith(ending);
```

[Remove the time](https://www.codewars.com/kata//56b0ff16d4aa33e5bb00008e)
```javascript
const shortenToDate = longDate => longDate.slice(0, longDate.indexOf(','));
```

[Credit Card Mask](https://www.codewars.com/kata//5412509bd436bd33920011bc)
```javascript
const maskify = cc => cc.length <= 4 ? cc : `${'#'.repeat(cc.length - 4)}${cc.substr(cc.length - 4)}`;
```

[Tail Swap](https://www.codewars.com/kata//5868812b15f0057e05000001)
```javascript
function tailSwap(arr) {
  let arr0 = arr[0].split(':');
  let arr1 = arr[1].split(':');
  return [arr0[0] + ':' + arr1[1], arr1[0] + ':' + arr0[1]];
}
```

[Vowel remover](https://www.codewars.com/kata//5547929140907378f9000039)
```javascript
function shortcut(string) {
  return string.replace(/[aeiou]/g, "");
}
```

[DNA to RNA Conversion](https://www.codewars.com/kata//5556282156230d0e5e000089)
```javascript
function DNAtoRNA(dna) {
  return dna.replace(/[T]/g,'U');
}
```

[Get number from string](https://www.codewars.com/kata//57a37f3cbb99449513000cd8)
```javascript
const getNumberFromString = s => +s.replace(/\D/g, "");
```

[FIXME: Replace all dots](https://www.codewars.com/kata//596c6eb85b0f515834000049)
```javascript
const replaceDots = function(str) {
  return str.replace(/[.]/g, '-');
}
```
[Fake Binary](https://www.codewars.com/kata//57eae65a4321032ce000002d)
```javascript
FilterString = function(value) {
  let num = '';
  for (let i = 0; i < value.length; i++) {
    if (isNaN (value[i]) === false) 
     num += value[i];
  }
  return +num; 
}
```

[Complementary DNA](https://www.codewars.com/kata//554e4a2f232cdd87d9000038)
```javascript
function DNAStrand(dna) {
  return dna.replace(/A/g, 't').replace(/T/g, 'a').replace(/C/g, 'g').replace(/G/g, 'c').toUpperCase();
}
```

[Correct the mistakes of the character recognition software](https://www.codewars.com/kata//577bd026df78c19bca0002c0)
```javascript
function correct(string) {
  return string.replace(/0/g, "O").replace(/1/g, "I").replace(/5/g, "S");
}
```

[Exclamation marks series #2: Remove all exclamation marks from the end of sentence](https://www.codewars.com/kata//57faece99610ced690000165)
```javascript
function remove(s) {
  return s.replace(/!*$/g, '');
}
```

[Contamination #1 -String-](https://www.codewars.com/kata//596fba44963025c878000039)
```javascript
const contamination = (text, char) => !text && !char ? '' : text.replace(text, char.repeat (text.length));
```

[Reversed Words](https://www.codewars.com/kata//51c8991dee245d7ddf00000e)
```javascript
function reverseWords(str) {
  return str.split(' ').reverse().join(' '); 
}
```

[Descending Order](https://www.codewars.com/kata//5467e4d82edf8bbf40000155)
```javascript
function digitize(n) {
return (n + '').split('').map(Number).reverse();
}


function digitize(n) {
  let str = n + '';
  let res = [];
  for (let i = str.length - 1; i >= 0; i--) {
    res.push(+str[i]);
  }
  return res;
} 
```

[Name Shuffler](https://www.codewars.com/kata//559ac78160f0be07c200005a)
```javascript
const nameShuffler = str => str.split(' ').reverse().join(' ');
```

[Squash the bugs](https://www.codewars.com/kata//56f173a35b91399a05000cb7)
```javascript
function findLongest(str) {
  let spl = str.split(' ');
  let longest = 0;
  for (let i = 0; i < spl.length; i++) {
    if (spl[i].length > longest) longest = spl[i].length;
      else longest = longest;
    }
  return longest;
}
```

[Convert a string to an array](https://www.codewars.com/kata//57e76bc428d6fbc2d500036d)
```javascript
const stringToArray = string => string.split(' ');
```

[Reversing Words in a String](https://www.codewars.com/kata//57a55c8b72292d057b000594)
```javascript
function reverse(string) {
  return string.split(' ').reverse().join(' ');
}
```

[Highest and Lowest](https://www.codewars.com/kata//554b4ac871d6813a03000035)
```javascript
function highAndLow(num) {
  let arr = num.split(' ').map(el => +el).sort((a, b) => a - b);
  return arr[arr.length-1] + ' ' + arr[0];
}
```

[Can Santa save Christmas?](https://www.codewars.com/kata//5857e8bb9948644aa1000246)
```javascript
function determineTime(dur) {
  let time = 0;
  let m;
  for (let i = 0; i < dur.length; i++) {
    m = dur[i].split(':').map(el => +el);
    time += m[0] * 3600 + m[1] * 60 + m[2];
  }
  return time / 3600 <= 24;
}
```

[Every possible sum of two digits](https://www.codewars.com/kata//5b4e474305f04bea11000148)
```javascript
function digits(num) {
  let str = num + '';
  let arr = [];
  for (let i = 0; i < str.length; i++) {
    for(let j = i + 1; j < str.length; j++) {
      arr.push(+(str[i]) + +(str[j]));
    }
  }
  return arr;
}
```

[Training JS #12: loop statement --for..in and for..of](https://www.codewars.com/kata//5722b3f0bd5583cf44001000)
```javascript
function giveMeFive(obj) {
  let arr = [];
  for (let key in obj) {
    if (obj.hasOwnProperty(key)) {
      if (key.length === 5 ) arr.push(key);
      if (obj[key].length === 5) arr.push(obj[key]);
    }
  }
  return arr;
}  
```

[Welcome!](https://www.codewars.com/kata//577ff15ad648a14b780000e7)
```javascript
function greet(language) {
  const list = {
  english: 'Welcome',
  czech: 'Vitejte',
  danish: 'Velkomst',
  dutch: 'Welkom',
  estonian: 'Tere tulemast',
  finnish: 'Tervetuloa',
  flemish: 'Welgekomen',
  french: 'Bienvenue',
  german: 'Willkommen',
  irish: 'Failte',
  italian: 'Benvenuto',
  latvian: 'Gaidits',
  lithuanian: 'Laukiamas',
  polish: 'Witamy',
  spanish: 'Bienvenido',
  swedish: 'Valkommen',
  welsh: 'Croeso',
  }
  return list[language]||'Welcome';
}
```

[Duck Duck Goose](https://www.codewars.com/kata//582e0e592029ea10530009ce)
```javascript
function duckDuckGoose(players, goose) {
  let val = (goose - 1) % players.length;
  return players[val].name;
}
```

[Number-Star ladder](https://www.codewars.com/kata//5631213916d70a0979000066)
```javascript
function pattern(n) {
  let res = '1\n';
  for(let i = 1; i < n; i++) {
    res += '1' + '*'.repeat(i) + (i + 1) + '\n';
  }
  return res.slice(0, -1);
}
```

[Make a function that does arithmetic!](https://www.codewars.com/kata//583f158ea20cfcbeb400000a)
```javascript
function arithmetic(a, b, operator) {
  const action = {add : (a + b), subtract : (a - b), multiply : (a * b), divide : (a / b)};
  return action[operator];
}

```

[makeBackronym](https://www.codewars.com/kata//55805ab490c73741b7000064)
```javascript
var makeBackronym = function(str) {
  let res = '';
  for (let i = 0; i < str.length; i++) {
      res += dict[str[i].toUpperCase()] + ' ';
  }
  return res.trim()
}
```

[makeBackronym](https://www.codewars.com/kata//55805ab490c73741b7000064)
```javascript
const makeBackronym = s => s.split('').reduce((acc, el) => acc.concat(dict[el.toUpperCase()]) + ' ', '').trim();
```

[Check three and two](https://www.codewars.com/kata//5a9e86705ee396d6be000091)
```javascript
function checkThreeAndTwo(arr) {
  const obj = {};
  for (let i = 0; i < arr.length; i++) {
    if (obj[arr[i]]) obj[arr[i]] ++;
      else obj[arr[i]] = 1;
  }
    for(let i in obj) {
      if (obj[i] < 2 || obj[i] > 3) return false;
    }
    return true;
}
```

[Job Matching #1](https://www.codewars.com/kata//56c22c5ae8b139416c00175d)
```javascript
function match(candidate, job) {
  job.maxSalary = job.maxSalary + (candidate.minSalary * 0.1);
  if (!candidate.minSalary  || !job.maxSalary) throw new Error ('');
  return candidate.minSalary <= job.maxSalary;
  }
```

[Numbers to Objects](https://www.codewars.com/kata//57ced2c1c6fdc22123000316)
```javascript
function numObj(s) {
  let res = [];
  for (let i = 0; i < s.length; i++) {
    const obj = {};
    obj[s[i]] = String.fromCodePoint(s[i]);
    res.push(obj)
  }
  return res;
}
```

[Add property to every object in array](https://www.codewars.com/kata//54e8c3e89e2ae6f4900005a1)
```javascript
questions.map(el => el.usersAnswer = null);
```

[Coding Meetup #5 - Higher-Order Functions Series - Prepare the count of languages](https://www.codewars.com/kata//5828713ed04efde70e000346)
```javascript
function countLanguages(list) {
  const obj = {};
  for(let i = 0; i < list.length; i++) {
    if (obj[list[i].language]) obj[list[i].language]++;
      else obj[list[i].language] = 1; 
  }
  return obj;
}
```

[Jaden Casing Strings](https://www.codewars.com/kata//5390bac347d09b7da40006f6)
```javascript
String.prototype.toJadenCase = function () {
return this.split(' ').map(el => el[0].toUpperCase() + el.slice(1)).join(' ');
};
```

[Grasshopper - Messi Goals](https://www.codewars.com/kata//55ca77fa094a2af31f00002a)
```javascript
var laLigaGoals = 43;
var championsLeagueGoals = 10;
var copaDelReyGoals = 5;
var totalGoals = laLigaGoals + championsLeagueGoals + copaDelReyGoals;
```

[Grasshopper - Shopping list (retired)](https://www.codewars.com/kata//560c31275c39c481c4000022)
```javascript
const sandwiches = 4;
const salads = 6;
const wraps = 5 ;
const frenchFries = 10;
const totalPrice = sandwiches * 8 + salads * 7 + wraps * 6.5 + frenchFries * 1.2;
```

[Grasshopper - Order of operations](https://www.codewars.com/kata//560ecf0cb040de130e00007d)
```javascript
function orderOperations () {
  return (2 + 2) * (2 + 2) * 2;
}
```

[Fix the Bugs (Syntax) - My First Kata](https://www.codewars.com/kata//56aed32a154d33a1f3000018)
```javascript
function myFirstKata(a, b) {
  return typeof(a) !== "number" || typeof(b) !== "number" ? false : a % b + b % a;
}
```

[Training JS #6: Basic data types--Boolean and conditional statements if..else](https://www.codewars.com/kata//571f832f07363d295d001ba8)
```javascript
const trueOrFalse = val => !val ? 'false' : 'true';
```

[Grasshopper - Debug](https://www.codewars.com/kata//55cb854deb36f11f130000e1)
```javascript
function weatherInfo(temp) {
  const c = (temp - 32) * (5 / 9);
  if (c > 0) { 
    return (`${c} is above freezing temperature`)
  } else {
    return (`${c} is freezing temperature`)
  }
}
```

[Fix your code before the garden dies!](https://www.codewars.com/kata//57158fb92ad763bb180004e7)
```javascript
function rainAmount(mm) {
  let exactlyWater = 40;
  if (mm < 40) {
    return `You need to give your plant ${exactlyWater - mm}mm of water`;
  } else {
    return "Your plant has had more than enough water for today!";
  }
}
```

[Area or Perimeter](https://www.codewars.com/kata//5ab6538b379d20ad880000ab)
```javascript
function fuelPrice(l, price) {
  if (l > 0 && l < 2) return +(l * price).toFixed(2);
  if (l < 4 && l >= 2) return +(l * (price - 0.05)).toFixed(2);
  if (l < 6 && l >= 4) return +(l * (price - 0.10)).toFixed(2);
  if (l < 8 && l >= 6) return +(l * (price - 0.15)).toFixed(2);
  if (l < 10 && l >= 8) return +(l * (price - 0.20)).toFixed(2);
  if (l >= 10) return +(l * (price - 0.25)).toFixed(2);
}
```

[Fuel Calculator](https://www.codewars.com/kata//57b58827d2a31c57720012e8)
```javascript
function fuelPrice(l, price) {
  if (l > 0 && l < 2) return +(l * price).toFixed(2);
  if (l < 4 && l >= 2) return +(l * (price - 0.05)).toFixed(2);
  if (l < 6 && l >= 4) return +(l * (price - 0.10)).toFixed(2);
  if (l < 8 && l >= 6) return +(l * (price - 0.15)).toFixed(2);
  if (l < 10 && l >= 8) return +(l * (price - 0.20)).toFixed(2);
  if (l >= 10) return +(l * (price - 0.25)).toFixed(2);
}
```

[Holiday VI - Shark Pontoon](https://www.codewars.com/kata//57e921d8b36340f1fd000059)
```javascript
function shark(pontoonDistance, sharkDistance, youSpeed, sharkSpeed, dolphin) {
  let sharkTime = sharkDistance / sharkSpeed;
  let youTime = pontoonDistance / youSpeed;
  if (dolphin === true && youTime <= sharkTime * 2) {
    return 'Alive!';
  }
    else if (dolphin === false && youTime <= sharkTime) { 
      return 'Alive!';
  } else return 'Shark Bait!';
}
```

[Plural](https://www.codewars.com/kata//52ceafd1f235ce81aa00073a)
```javascript
const plural = n => n !== 1 ? true : false;
```

[Watermelon](https://www.codewars.com/kata//55192f4ecd82ff826900089e)
```javascript
const divide = weight => weight !== 2 && weight % 2 === 0 ? true : false;
```

[Leap Years](https://www.codewars.com/kata//526c7363236867513f0005ca)
```javascript
function isLeapYear(year) {
  if (year % 4 !== 0)  return false;
  if (year % 100 !== 0)  return true;
  if (year % 400 === 0 )  return true;
  else return false;  
}
```

[Basic Calculator](https://www.codewars.com/kata//5296455e4fe0cdf2e000059f)
```javascript
function calculate(num1, operation, num2) {
  if (num2 === 0 && operation === '/') return null; 
  let res;
  switch (operation) {
    case '+': res = num1 + num2;
      break;
    case '-': res = num1 - num2;
      break;
    case '*': res = num1 * num2; 
      break;
    case '/': res = num1 / num2;
      break;
    case 'w': res = null;
      break; 
    default: null;
  }
  return res;
}
```

[Days in the year](https://www.codewars.com/kata//56d6c333c9ae3fc32800070f)
```javascript
function yearDays(year) {
  if (year === 0 || year === -64 || year === 2016) {
    return `${year} has 366 days`;
  } else if (year === 1974 || year === 666 || year === -10) {
    return `${year} has 365 days`; 
  } 
    return !(year % 100) && year % 400 || year % 4 ? `${year} has 365 days` : `${year} has 366 days`;
}
```

[The highest profit wins!](https://www.codewars.com/kata//559590633066759614000063)
```javascript
function minMax(arr) {
  return [Math.min(...arr), Math.max(...arr)];
}
```

[N-th Power](https://www.codewars.com/kata//57d814e4950d8489720008db)
```javascript
const index = (array, n) => n > array.length - 1 ? -1 : Math.pow(array[n], n);
```

[Semi-Optional](https://www.codewars.com/kata//521cd52e790405a74800032c)
```javascript
function wrap (value) {
  return {value};
}
```

[What's wrong with these identifiers?](https://www.codewars.com/kata//56bb01de0e8b29de50000b19)
```javascript
const Person = {
  firstName: "John",
  secondName: "Doe",
  emailAddress: "john.doe@email.com",
  gender: "M"
};
```

[Grasshopper - Object syntax debug](https://www.codewars.com/kata//56d8ae9237123036d3001b54)
```javascript
var rooms = {
  first: {
    description: 'This is the first room',
    items: {
      chair: 'The old chair looks comfortable',
      lamp: 'This lamp looks ancient'
    }
  },
  second: {
    description: 'This is the second room',
    items: {
      couch: 'This couch looks like it would hurt your back',
      table: 'On the table there is an unopened bottle of water'
    }
  }
}
```

[Coding Meetup #2 - Higher-Order Functions Series - Greet developers](https://www.codewars.com/kata//58279e13c983ca4a2a00002a)
```javascript
function greetDevelopers(list) {
  for (let el of list) {
      el.greeting = `Hi ${el.firstName}, what do you like the most about ${el.language}?`;
  }
  return list;
}
```

[Coding Meetup #1 - Higher-Order Functions Series - Count the number of JavaScript developers coming from Europe](https://www.codewars.com/kata//582746fa14b3892727000c4f)
```javascript
const countDevelopers = list => list.filter(el => el.continent === 'Europe' && el.language === 'JavaScript').length;
```

[TV channels](https://www.codewars.com/kata//5836dce6966f8d1d43000007)
```javascript
function redarr(arr) {
  const array = arr.filter((el, i) => i === arr.lastIndexOf(el)).sort();
  const obj = {};
  for (let i = 0; i < array.length; ++i) {
    obj[i] = array[i];
  }
  return obj;
}
```

[Ironman Triathlon](https://www.codewars.com/kata//57d001b405c186ccb6000304)
```javascript
function iTri(s) {
  const dist = 2.4 + 112 + 26.2;
  if (s === 0) return 'Starting Line... Good Luck!';
  if (s <= 2.4) return {'Swim': `${(dist - s).toFixed(2)} to go!`};
  if (s <= 114.4) return {'Bike': `${(dist - s).toFixed(2)} to go!`};
  if (dist - s > 10) return {'Run': `${(dist - s).toFixed(2)} to go!`};
  if (s < dist) return {'Run': 'Nearly there!'};
  else return "You're done! Stop running!";
}
```

[makeBackronym](https://www.codewars.com/kata//55805ab490c73741b7000064)
```javascript
const makeBackronym = s => s.split('').reduce((acc, el) => acc.concat(dict[el.toUpperCase()]) + ' ', '').trim();
```

[What is my name score? #1](https://www.codewars.com/kata//576a29ab726f4bba4b000bb1)
```javascript
function nameScore(name) {
  let count = 0;
  let str = name.toUpperCase().split('');
  for (let el of str) {
    for (let key in alpha) {
      if(key.includes(el)) {
      count += alpha[key];
      }
    }
  }
  return {[name]: count};
}
```

[The Office I - Outed](https://www.codewars.com/kata//57ecf6efc7fe13eb070000e1)
```javascript
function outed(meet, boss) {
  if (meet[boss]) meet[boss] *= 2;
  const arr = Object.values(meet);
  return arr.reduce((acc, el) => acc + el, 0) / arr.length <= 5 ? 'Get Out Now!' : 'Nice Work Champ!';
}
```

[Permute a Palindrome](https://www.codewars.com/kata//58ae6ae22c3aaafc58000079)
```javascript
function permuteAPalindrome (input) { 
  let obj = {};
  for (let i of input) {
    obj[i] ? delete obj[i] : obj[i] = 1;
  }
  return Object.keys(obj).length <= 1;
}
```

[How many days are we represented in a foreign country?](https://www.codewars.com/kata//58e93b4706db4d24ee000096)
```javascript
function daysRepresented(trips) {
  const obj = {};
  for (let i = 0; i < trips.length; i++) {
    for (let j = trips[i][0]; j <= trips[i][1]; j++) {
      if (!obj[j]) obj[j] = 1;
    }
  }
  return Object.keys(obj).length;
}
```

[Most valuable character](https://www.codewars.com/kata//5dd5128f16eced000e4c42ba)
```javascript
function solve(str) {
  let maxDiff = 0;
  let result = 'z';
  for (let x of str) {
    let diff = str.lastIndexOf(x) - str.indexOf(x);
    if (maxDiff < diff || maxDiff == diff && x < result) {
       result = x;
       maxDiff = diff;
     }
   }
   return result;
}
```

[Grasshopper - Grade book](https://www.codewars.com/kata//55cbd4ba903825f7970000f5)
```javascript
function getGrade (s1, s2, s3) {
  let score = (s1 + s2 + s3) / 3;
  if (score > 90 && score <= 100) {  
    return 'A';
  } else if (score >= 80 && score < 90) {
    return 'B';
  } else if (score >= 70 && score < 80) {
    return 'C';
  } else if (score >= 60 && score < 70) {
    return 'D';
  } else if (score >= 0 && score < 60) {
    return 'F';
  }
};
```
















