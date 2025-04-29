1. The value variable always return the string type so '2' + '3' ends up string concatenation which result in '23' not 5. As we can see in the result variable it shows the string type.

2. I would fix by assigning number value to both num1 and num2 by doing.
let num1 = Number(document.getElementById("num1").value);
let num2 = Number(document.getElementById("num2").value);