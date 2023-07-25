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

  - ### Heads and Legs | [:arrow_up:UP](#kata)
    ```javascript
    function animals(heads, legs){
      for(var i = 0; i <= heads; i++){
        if( (i * 4 + (heads- i) * 2) == legs){
          return [heads- i,i];
        }
      }
      return 'No solutions';
    }

    console.log(animals(72, 200)) // [44,28]
    console.log(animals(25, 555)) // "No solutions"
    
    ```
    <br>
    <br>

  - ### Hello, Name or World! | [:arrow_up:UP](#kata)
    ```javascript
    
    function hello(name) {
      return `Hello, ${name ? name.at(0).toUpperCase() + name?.slice(1).toLowerCase() : 'World'}!`
    }

    console.log(hello('alice')) // "Hello, Alice!"
    console.log(hello()) // "Hello World!"
    ```
    <br>
    <br>
    
  - ###  | [:arrow_up:UP](#kata)
    ```javascript

    

    console.log(()) //
    console.log(()) //
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
