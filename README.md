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