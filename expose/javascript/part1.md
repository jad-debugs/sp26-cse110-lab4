1. values added:  20
2. final results:  20
3. you should not use var because it is function scoped, instead of block scoped which can cause bugs and harder to read code
4. values added:  20
5. This throws an error, because using let is block scoped within the if statement, and since we try to use result outside the  if, an error is thrown
6. Nothing, code crashes before this, due to the error on line 7, which i go into depth in the next question.
7. This throws an error for multiple reasons, first it is block scope, so we cant use result outside of the if. Second, we reassigned result on a const variable which is not allowed, which happened on line 7.
