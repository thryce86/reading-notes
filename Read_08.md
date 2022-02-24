same basic operators except for these


Exponentiation assignment	x **= f()	x = x ** f()
Left shift assignment	x <<= f()	x = x << f()
Right shift assignment	x >>= f()	x = x >> f()
Unsigned right shift assignment	x >>>= f()	x = x >>> f()



so still need to declare variables explictly 


let x = f();




Evaluation example 2
y = [ f(), x = g() ] also evaluates from left to right:

so left to right up and down 



This is a bit off.

Equal (==)	Returns true if the operands are equal.	3 == var1
"3" == var1

3 == '3'
Not equal (!=)	Returns true if the operands are not equal.	var1 != 4
var2 != "3"
Strict equal (===)	Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS.	3 === var1
Strict not equal (!==)	Returns true if the operands are of the same type but not equal, or are of different type.	var1 !== "3"
3 !== '3'



So the syntax is a lot like SAS ....

let i = 0;
do {
  i += 1;
  console.log(i);
} while (i < 5);



so you can use these as pseudofunctions?


markLoop:
while (theMark === true) {
   doSomething();
}