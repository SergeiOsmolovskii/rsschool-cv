# Asmalouski Siarhei
***
__Contact__

* _Phone: 8 (025) 725-67-82_
* _E-mail: osmolovskii_sergei@mail.ru_

__About me__


__Technical skills__

* HTML
* CSS
* SASS
* Bootstrap 4
* JS

__Sample code__

```
function validParentheses(parens) {
  const openBracket = ['(','[','{']; 
  const closeBracket = [')',']','}'];
  let stack = [];
  for(let i=0; i<parens.length; i++) {
    if (openBracket.includes(parens[i])) {
      stack.push(parens[i]);
    } else {
        if (closeBracket.indexOf(parens[i]) === openBracket.indexOf(stack[stack.length-1])) {
          stack.pop();
        } else return false; 
      }   
    }
  if (stack.length == 0) {
    return true;
  } else return false;
}
}
```

__Work experience__

__Education__

* Belarusian-Russian University
  * Electric Drive and Automation of Industrial Units. Automatic Electric Drives (2013-2018).
  * Master’s degree course electrical power industry and electrical engineering (2018-2019).
* Courses 
  *  Peter the Great St.Petersburg Polytechnic University. Intelligent Control Systems (2017).

__Languages__

* English: A2 (Pre-Intermediate)