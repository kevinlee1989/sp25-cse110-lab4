1. 3, Since i is defined as "var", it will be function scope and accessible from anywhere in that function. After going through the for loop i will become 3 due to the length of the prices array. Finally, console.log(i) will print 3 without any error.

2. 150, Since discountedPrice is also defined as "var", it will be function scope and accessible anywhere in that function. While going through the loop discountedPrice will be keep updated and eventually have the last value which is 300 * (1 -0.5) = 150. Finally, console.log(discountedPrice) will executed after iterating for loop, so the last value of the discountedPrice = 150 and it will be printed in the console due to the line 13.

3. 150, Since finalPrice is also defined as "var", it will be function scope and accessible anywhere in that function. It is also same reason as problem 1 and 2, the for loop will keep executed until the last price and finalPrice = (150 * 100) / 100 and the console.log statement which is after the for loop will print 150.

4. The function discountPrices will return [50, 100, 150]. The variable discounted is also defined as "var" so it is accessible anywhere in the function block which will successfully return the corressponding array of prices.

5. The code will cause the reference error: i is not defined. The reason why the code occurs the error is that i is defined as "let" which is only accessible inside the block where the i is defined. Line  12 is outside  the for loop so it can not access to variable i.

6. The code will cause the reference error: discountedPrice is not defined. The reason is exact same with problem 5. The variable is defined as let inside the for loop and the console statement is trying to access outside the for loop.

7. The code will output 150 without an error. Although it is defined as "let" the finalPrice is defined at the top of the function. It is also block scope but it is also accessible anywhere in the function(function-level block scope). Since line 14 is in the function where it is the same block as the place where finalPrice is defined, it is accessible in line 14.

8. The code will return the array of prices which is [50, 100, 150] without an error due to the same reason with problem 7. The array discounted is also defined as "let" but it is also function-level block scope so that line 16 return statement also can access to the variable.

9. The code will output ReferenceError: i is not defined. Since i is defined as "let" in the for loop the console.log(i) which is outside the for loop can not access to the variable i.

10. The code will output 3. Since length is defined as "const" which is block scope but it is also accessible anwhere in the function due to its location which is going to be function-leve block scope. There are 3 prices so the length will output 3.

11. The function discountPrices will return [50, 100, 150]. The variable discounted is also defined as "const". Even it if is defined as "const", the variable discounted is also function-level block scope so it is accessible anywhere in the function block which will successfully return the corressponding array of prices.

12. 
A. student.name
B. student["Grad Year"]
C. student.greeting()
D. student["Favorite Teacher"].name
E. student.courseLoad[0]

13. 
A. 32, '3' is string type and 2 is number, if there is at least one string type in the operator "+" then it is connected to string variable.
B. 1, '3' is string type and 2 is number, but for number operator '-', '3' automatically converts to number type and calculate the equation.
C. 3, null in number is converted to 0 so 3 + 0 = 0
D. 3null, '3' is string type and it will be connected to 3 which will be 3null.
E. 4, true in number is converted to 1 so 1 + 3 =4
F. 0, false in number is converted to 0 and also null in number is coverted in 0 so 0 + 0 = 0
G. 3undefined, same reason as D. '3' is string type so undefined is connected after 3 so 3undefined.
H. NaN, '3' converts to number 3 because '-' is number operator but undefined cannot be converted in to the number so 3 - NaN = Nan

14. 
A. true, '2' converts to number 2 and 2 > 1 -> True
B. false, Comparing the string type is based on lexicographic comparison so '2' < '12' -> false
C. true, == is Loose equality which converts the type automatically. '2' converts in to number 2 and 2 == 2 -> True
D. false, === is strict equality which compares also the type of the variables. number 2 and string '2' is not the same type. 
E. false, true in number converts to 1 and 1 is not equal to 2.
F. true, Boolean(2) is true and the type of the both variables are boolean so true === true -> true

15. The difference between == and === operators is the strictness. == operator converts the type and compares while === operators compare both value and the type.

17. The function returns [2,4,  6]. First the modify([1,2,3], doSomething) will be called with the following parameters which is an array and a callback funtion. It loops through the array and applies the callback to each element. The callback function "doSomething" simply doubles the input value. Lastly, the elements 1,2,3 will become 2,4,6 respectively.
Callback function is a function passed as an argument to another function so that it can run later. There are several reason why we use callback() such as control execution order, encourage reusability, and handle asynchronous tasks.

19. 
1
4
3
2
