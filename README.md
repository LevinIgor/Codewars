# **Collection of solved tasks from the [codewars](https://www.codewars.com) site**

There will be examples of solutions, **I do not recommend using the offered code to solve your tasks**. I want to warn you that if you try to use the answers shown, you are likely **to be blocked by the site**. The repository was created primarily as a collection of examples for possible study, and help newcomers.

# **Kata**

  - **[8 kyu](#8-kyu)** <br>
  - **[7 kyu](#7-kyu)** <br>
  - **[6 kyu](#6-kyu)** <br>
  - **[5 kyu](#5-kyu)** <br>
  - **[4 kyu](#4-kyu)** <br>
  - **[3 kyu](#3-kyu)** <br>
  - **[2 kyu](#2-kyu)** <br>
  - **[1 kyu](#1-kyu)** <br> 
  <br>
  <br>
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
## 7 Kyu
## 6 Kyu
## 5 Kyu
## 4 Kyu
## 3 Kyu
## 2 Kyu
## 1 Kyu
