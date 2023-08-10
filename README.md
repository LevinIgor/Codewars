# **JavaScript Collection of solved tasks from the [codewars](https://www.codewars.com) site**


There will be examples of solutions, **I do not recommend using the offered code to solve your tasks**. I want to warn you that if you try to use the answers shown, you are likely **to be blocked by the site**. The repository was created primarily as a collection of examples for possible study, and help newcomers.
<br>
<br>


![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/t/LevinIgor/Codewars)
![GitHub Repo stars](https://img.shields.io/github/stars/LevinIgor/Codewars)
![GitHub forks](https://img.shields.io/github/forks/LevinIgor/Codewars)
![GitHub contributors](https://img.shields.io/github/contributors/LevinIgor/codewars)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/LevinIgor/Codewars)
![GitHub last commit](https://img.shields.io/github/last-commit/LevinIgor/codewars)


# **Kata**

  - **[8 - kyu](#8-kyu)** <br>
  - **[7 - kyu](#7-kyu)** <br>
  - **[6 - kyu](#6-kyu)** <br>
  - **[5 - kyu](#5-kyu)** <br>
  - **[4 - kyu](#4-kyu)** <br>
  - **[3 - kyu](#3-kyu)** <br>
  - **[2 - kyu](#2-kyu)** <br>
  - **[1 - kyu](#1-kyu)** <br> 
<br>


## 8 Kyu

  - ### Heads and Legs | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript
    function animals(heads, legs){
      for(var i = 0; i <= heads; i++){
        if( (i * 4 + (heads- i) * 2) == legs){
          return [heads- i,i];
        }
      }
      return 'No solutions';
    }

    
    ```
    <br>
    <br>

  - ### Hello, Name or World! | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript
    
    const hello = name => return `Hello, ${name ? name.at(0).toUpperCase() + name?.slice(1).toLowerCase() : 'World'}!`
    
    ```
    <br>
    <br>
    
  - ### A Strange Trip to the Market | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const isLockNessMonster = s => s.includes('tree fiddy') || s.includes('3.50') || s.includes('three fifty')
    
    ```
    <br>
    <br>
    
  - ### Add new item (collections are passed by reference) | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const addExtra = listOfNumbers => [...listOfNumbers,'cock']
    
    ```
    <br>
    <br>

  - ### Exclamation marks series #4: Remove all exclamation marks from sentence but ensure a exclamation mark at the end of string | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const remove = string => string.replace(/!/g, '') + '!'
    
    ```
    <br>
    <br>


  - ### Exclamation marks series #2: Remove all exclamation marks from the end of sentence | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const remove = s => s.replace(/!+$/, '');
    
    ```
    <br>
    <br>

  - ### Grasshopper - Variable Assignment Debug | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    var a = "dev"
    var b = "Lab"
    
    var name = a + b
    ```
    <br>
    <br>

  - ### Return Two Highest Values in List | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const twoHighest = arr => [...new Set(arr)].sort((a,b) => a-b).slice(-2).reverse()
    
    ```
    <br>
    <br>

  - ### How old will I be in 2099? | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const calculateAge = (m, n) => {
      if(m == n) return 'You were born this very year!';
    
      const year = Math.abs(m-n) == 1 ? 'year' : 'years';
    
      if(m < n) return "You are "+(n-m)+' '+year+' old.';
      if(m > n) return "You will be born in "+(-n+m)+' '+year+'.';
    }
    ```
    <br>
    <br>

  - ### Ensure question  | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const ensureQuestion = s => s.endsWith('?') ? s : s + '?'
    
    ```
    <br>
    <br>

  - ### Total pressure calculation  | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function solution(M1, M2, m1, m2, V, T) {
    		M1 = m1 * 0.001/M1;
        M2 = m2 * 0.001/M2;
        T = T + 273.15;
    	  const R = 0.082;
    
    	  return (((M1 + M2) * R * T) / V) * 1000;
    }
    
    ```
    <br>
    <br>

  - ### Enumerable Magic #1 - True for All? | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const all = ( arr, fun ) => arr.every(fun)

    ```
    <br>
    <br>

  - ### Parse float | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const parseF = s =>  isNaN(parseFloat(s)) ? null : parseFloat(s)

    ```
    <br>
    <br>

  - ### SpeedCode #2 - Array Madness | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const arrayMadness = (a, b) => a.reduce((acc, x) => acc + x**2, 0) > b.reduce((acc, x) => acc + x**3, 0) 

    ```
    <br>
    <br>

  - ### easy logs | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const logs = (x , a, b) =>  (Math.log(a*b) / Math.log(x))

    ```
    <br>
    <br>

  - ### Classy Classes | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    class Person {

      constructor(name, age) {
        this.name = name;
        this.age = age;
      }
      
      get info() {
        return `${this.name}s age is ${this.age}`;
      }
    }
    ```
    <br>
    <br>

  - ### Pole Vault Starting Marks | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const startingMark = bodyHeight => +(bodyHeight * 3.9354 + 3.4681).toFixed(2);

    ```
    <br>
    <br>

  - ### Training JS #6: Basic data types--Boolean and conditional statements if..else | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const trueOrFalse =(val) => Boolean(val).toString()

    ```
    <br>
    <br>
    
  - ### Fuel Calculator: Total Cost | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function fuelPrice(litres, pricePerLiter) {
      var discount = Math.min(Math.floor(litres/2) * 0.05, 0.25);
      var price = litres * (pricePerLiter - discount);
      return Math.round(price*100) / 100;
    }

    ```
    <br>
    <br>

  - ### Days in the year | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const yearDays = year => `${year} has 36${6 - !!(year % 400 && !(year % 100) || year % 4)} days`;

    ```
    <br>
    <br>
    
  - ### Arguments to Binary addition | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const arr2bin = arr => arr.filter(x => typeof x == 'number').reduce((x, y) => x + y, 0).toString(2);

    ```
    <br>
    <br>
    
  - ### Training JS #34: methods of Math---pow() sqrt() and cbrt() | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function cutCube(volume,n){
      return !(Math.cbrt(n) % 1) && !(Math.cbrt(volume / n) % 1);
    }

    ```
    <br>
    <br>
    
  - ### Training JS #17: Methods of String object--indexOf(), lastIndexOf() and search() | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const firstToLast = (str,c) => (str.indexOf(c) < 0) ? -1 : str.lastIndexOf(c) - str.indexOf(c)

    ```
    <br>
    <br>
    
  - ### Implement Array.prototype.filter() | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    Array.prototype.filter = function (func) {
      const result = []
      this.forEach(el => func(el) ? result.push(el) : null)      
      return result
    }

    ```
    <br>
    <br>
    
  - ### Job Matching #1 | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function match(candidate, job) {
        if(!candidate.minSalary || !job.maxSalary) throw "Error!!";
        return (candidate.minSalary * 0.9) <= job.maxSalary;
    }

    ```
    <br>
    <br>
    
  - ### Lexical this | 8 kyu | [:arrow_up:UP](#kata)
    ```javascript

     var Person = function(){
        var person = {
          _name: "Leroy",
          _friends: [],
          fillFriends(f){
            this._friends.push(...f);
          }
        }
        return person;
    }

    ```
    <br>
    <br>
    
## 7 Kyu

  - ### ASCII letters from Number | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function convert(number){
      const arr = []
      
      for(let i = 0; i < number.length; i+=2){
        arr.push(String.fromCharCode(number.substr(i,2)))
      }
      
      return arr.join('')
     }

    ```
    <br>
    <br>
    
  - ### Find the next perfect square! | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function findNextSquare(sq) {
      return Math.sqrt(sq)%1? -1 : Math.pow(Math.sqrt(sq)+1,2);
    }

    ```
    <br>
    <br>
    
  - ### Ones and Zeros | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const binaryArrayToNumber = arr => {
      return parseInt(arr.join(""), 2)
    };

    ```
    <br>
    <br>
    
  - ### Sum of the first nth term of Series | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function SeriesSum(n) {
      var sum = 0;
      for(var i = 0; i < n; i++) {
        sum += 1 / (3 * i + 1);
      }
      return sum.toFixed(2);
    }

    ```
    <br>
    <br>
    
  - ### Sort array by string length | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

     let sortByLength = arr => arr.sort((a,b) => a.length - b.length);

    ```
    <br>
    <br>
    
  - ### Find the middle element | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

     const gimme = function (arr) {
        return arr.indexOf([...arr].sort((x, y) => x > y)[1]);
     };


    ```
    <br>
    <br>
    
  - ### Round up to the next multiple of 5 | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

     function roundToNext5(n){
        return Math.ceil(n/5)*5;
      }


    ```
    <br>
    <br>
    
  - ### Simple Fun #176: Reverse Letter | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

     function reverseLetter(str) {
        return str.replace(/[^a-z]/gi,'').split('').reverse().join('')  
    }


    ```
    <br>
    <br>
    
  - ### Summing a number's digits | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function sumDigits(number) {
      return `${Math.abs(number)}`.split('').reduce((acc,el) => acc + +el,0)
    }


    ```
    <br>
    <br>
    
  - ### Check the exam | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function checkExam(array1, array2) {
      let result = 0;
      
      for(let i in array1){
        if(array2[i] === '') continue;
        array1[i] === array2[i] ? result+=4 : result-=1;
      }
      
      return Math.max(result,0)
    }


    ```
    <br>
    <br>
    
  - ### Fix string case | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function solve(s){
        return s.match(/[a-z]/g).length >= s.length / 2 ? s.toLowerCase() : s.toUpperCase()
    }


    ```
    <br>
    <br>
    
  - ### Triangular Treasure | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    function triangular( n ) {
      return n > 0 ? n * (n + 1) / 2 : 0;
    }


    ```
    <br>
    <br>
    
  - ### Most digits | 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const findLongest = l => l.reduce((a, b) => (`${b}`.length > `${a}`.length) ? b : a);


    ```
    <br>
    <br>
    
  - ### Reverse a Number 7 kyu | [:arrow_up:UP](#kata)
    ```javascript

    const reverseNumber = n => (n > 0 ? 1 : -1) * Math.abs(n).toString().split('').reverse().join('')


    ```
    <br>
    <br>
    
  - ### Minimize Sum Of Array (Array Series #1) | [:arrow_up:UP](#kata)
    ```javascript

    function minSum(arr) {
      const l = arr.length;
      const sorted = arr.sort((a, b) => b - a);
      const max = sorted.slice(0, l/2);
      const min = sorted.slice(l/2, l).reverse();
      
      return max.reduce((sum, el, i) => sum + el * min[i], 0);
    }


    ```
    <br>
    <br>
    
  - ### Moves in squared strings (I) | [:arrow_up:UP](#kata)
    ```javascript

    const vertMirror = s => s.map(s => [...s].reverse().join(''));
    const horMirror = s => s.reverse();
    
    const oper = (fct, s) => fct(s.split("\n")).join("\n");

    ```
    <br>
    <br>

  - ### All unique | [:arrow_up:UP](#kata)
    ```javascript

    let hasUniqueChars = (str) => new Set(str).size === str.length;

    ```
    <br>
    <br>
    
  - ### Palindrome chain length | [:arrow_up:UP](#kata)
    ```javascript

    const palindromeChainLength = n => {
      let count = 0;
    
      while(+[...`${n}`].reverse().join('') !== n){
        n+= +[...`${n}`].reverse().join('')
        count++;
      }
      
      return count
    };

    ```
    <br>
    <br>
    
  - ### Speed Control | [:arrow_up:UP](#kata)
    ```javascript

    const gps = (s, x) => {

      if (x.length<=1) {
        return 0;
      }
      
      let output = [];
      for (let i = 0; i < x.length-1; i++) { 
        output.push((x[i+1]-x[i])*3600/s);
      }
      
      return Math.max(...output);
    }

    ```
    <br>
    <br>
    
  - ### Coding Meetup #2 - Higher-Order Functions Series - Greet developers | [:arrow_up:UP](#kata)
    ```javascript

     const greetDevelopers = list => list.map(dev => ({...dev, greeting: `Hi ${dev.firstName}, what do you like the most about ${dev.language}?`}));

    ```
    <br>
    <br>
    
  - ### Halving Sum | [:arrow_up:UP](#kata)
    ```javascript

     const halvingSum = n => n > 1 ? n + halvingSum(n / 2 | 0) : n

    ```
    <br>
    <br>
    
  - ### max diff - easy | [:arrow_up:UP](#kata)
    ```javascript

     function maxDiff(list) {
       return list.length ? Math.max(...list) - Math.min(...list) : 0;
     };

    ```
    <br>
    <br>
    
  - ### Over The Road | [:globe_with_meridians:Source](https://www.codewars.com/kata/5f0ed36164f2bc00283aed07/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

     function maxDiff(list) {
       return list.length ? Math.max(...list) - Math.min(...list) : 0;
     };

    ```
    <br>
    <br>
    
  - ### Simple beads count | [:globe_with_meridians:Source](https://www.codewars.com/kata/58712dfa5c538b6fc7000569/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

     function countRedBeads(n) {
       return n < 2 ? 0 : 2 * n - 2;
     }

    ```
    <br>
    <br>
    
  - ### Boiled Eggs | [:globe_with_meridians:Source](https://www.codewars.com/kata/52b5247074ea613a09000164/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    function cookingTime(eggs) {
      return 5 * Math.ceil(eggs / 8);
    }

    ```
    <br>
    <br>
    
  - ### Simple remove duplicates | [:globe_with_meridians:Source](https://www.codewars.com/kata/5ba38ba180824a86850000f7/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

     function solve(arr){
       return arr.filter((val,i) => arr.lastIndexOf(val) == i);
     }

    ```
    <br>
    <br>
    
  - ### Find the nth Digit of a Number | [:globe_with_meridians:Source](https://www.codewars.com/kata/577b9960df78c19bca00007e/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    var findDigit = function(num, nth){
      if(nth <= 0) return -1
      num = `${Math.abs(num)}`
      
      return num.length >= nth ? +num.at(num.length - nth) : 0
    }

    ```
    <br>
    <br>
    
  - ### esreveR | [:globe_with_meridians:Source](https://www.codewars.com/kata/5413759479ba273f8100003d/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

     reverse = function(array) {
       return array.map((c, i) => array[array.length - 1 - i]);
     }

    ```
    <br>
    <br>
    
  - ### Sum of array singles | [:globe_with_meridians:Source](https://www.codewars.com/kata/59f11118a5e129e591000134/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

     function repeats(arr){
       return arr.reduce((acc,el) => arr.indexOf(el) === arr.lastIndexOf(el) ? acc+=el : acc,0)
     };

    ```
    <br>
    <br>
    
  - ### Gauß needs help! (Sums of a lot of numbers). | [:globe_with_meridians:Source](https://www.codewars.com/kata/54df2067ecaa226eca000229/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

     function f(n){
       if(typeof n !== 'number' || !Number.isInteger(n) || n <= 0) return false
       return ((1 + n)*n)/2
     };

    ```
    <br>
    <br>
    
  - ### Alphabetical Addition | [:globe_with_meridians:Source](https://www.codewars.com/kata/5d50e3914861a500121e1958/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    function addLetters(...letters) {
      const alpha = 'zabcdefghijklmnopqrstuvwxy';
      const sum = letters.reduce((sum, letter) => sum + alpha.indexOf(letter), 0) % 26;
      return alpha[sum];
    }

    ```
    <br>
    <br>
    
  - ### Filter the number | [:globe_with_meridians:Source](https://www.codewars.com/kata/55b051fac50a3292a9000025/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    const FilterString = value => +value.replace(/\D/g, '');

    ```
    <br>
    <br>
    
  - ### Simple Fun #74: Growing Plant | [:globe_with_meridians:Source](https://www.codewars.com/kata/58941fec8afa3618c9000184/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    function growingPlant(upSpeed, downSpeed, desiredHeight) {
      let count = 0, height = 0;
      while(true){
        count++;
        height+=upSpeed;
        if(height >= desiredHeight) return count;
        height-=downSpeed;
      }
    }

    ```
    <br>
    <br>
    
  - ### Coloured Triangles | [:globe_with_meridians:Source](codewars.com/kata/5a25ac6ac5e284cfbe000111/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    function triangle(row) {
      let result = ''
      if(row.length == 1) result = row;
      
      for(let i = 0; i < row.length - 1; i++){
        if(row[i] === row[i+1]) result+= row[i]
        else result+= 'RGB'.replace(row[i],'').replace(row[i+1],'')
      }
      
      if(row.length > 1) return triangle(result)
      else return result
    }

    ```
    <br>
    <br>
    
  - ### Strong Number (Special Numbers Series #2) | [:globe_with_meridians:Source](https://www.codewars.com/kata/5a4d303f880385399b000001/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    function strong(n) {
      return [1,2,145,40585].includes(n) ? 'STRONG!!!!' : 'Not Strong !!'
    }

    ```
    <br>
    <br>
    
  - ### Help the Fruit Guy | [:globe_with_meridians:Source](https://www.codewars.com/kata/557af4c6169ac832300000ba/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    function removeRotten(arr){
      return arr ? arr.map(x=>x.replace('rotten', '').toLowerCase()) : [] ;
    }

    ```
    <br>
    <br>
    
  - ### Currying functions: multiply all elements in an array | [:globe_with_meridians:Source](https://www.codewars.com/kata/586909e4c66d18dd1800009b/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    const multiplyAll = arr => n => arr.map(x => n * x);

    ```
    <br>
    <br>
    
  - ### Alternate case | [:globe_with_meridians:Source](https://www.codewars.com/kata/57a62154cf1fa5b25200031e/javascript)  | [:arrow_up:UP](#kata)
    ```javascript

    function alternateCase(s) {
      return [...s].map(el => el === el.toLowerCase() ? el.toUpperCase() : el.toLowerCase()).join('')
    }


    ```
    <br>
    <br>
    
## 6 Kyu
## 5 Kyu
## 4 Kyu
## 3 Kyu
## 2 Kyu
## 1 Kyu
