1. 20
2. 20
3. the "var" has a function scope not block scope, so even if we define "var" inside the block, it is also accessible in function anywhere outside the block so it can have a unexpected bug.

4. 20
5. The code returns ReferenceError: result is not defined. The reason why this code is getting error is that "let" has a block scope so it is not accessible outside the block. When we try to access the "let" variable from outside of the block, the variable that defined by "let" will not be accessible and end up refernce error.

6. The code returns TypeError: Assignment to constant variable. The reason why this code gets error is that we can not re-assign the variable which was defined as "const". However, the code is trying to modify the value of result which will end up error.
7.  The code returns TypeError: Assignment to constant variable. It is the same reason why this code gets error. The code is trying to re-assign the value of result which is defined as "const"