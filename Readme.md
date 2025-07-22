# Operators in C++
# Pratyush Saha
# PRN-24070123078
In C++, operators are symbols that perform operations on variables and values (like +, -, *, etc.).
They help in performing calculations, comparisons, and logical decisions.

Operators are grouped into categories based on their function:

1. Arithmetic Operators
Used for mathematical operations.

Operator	Function	Example
+	Addition	a + b (adds two values)
-	Subtraction	a - b
*	Multiplication	a * b
/	Division	a / b (integer division if both are int)
%	Modulus (Remainder)	a % b (remainder after division)

2. Relational (Comparison) Operators
Used to compare values (results in true or false).

Operator	Function	Example
==	Equal to	a == b
!=	Not equal to	a != b
>	Greater than	a > b
<	Less than	a < b
>=	Greater than or equal to	a >= b
<=	Less than or equal to	a <= b

3. Logical Operators
Used for decision-making (combining conditions).

Operator	Function	Example
&&	Logical AND (true if both true)	(a > 0 && b > 0)
`		`
!	Logical NOT (inverts condition)	!(a > 0)

4. Assignment Operators
Used to assign values to variables.

Operator	Function	Example
=	Assign value	x = 5
+=	Add and assign	x += 3 (same as x = x + 3)
-=	Subtract and assign	x -= 2
*=	Multiply and assign	x *= 4
/=	Divide and assign	x /= 2
%=	Modulus and assign	x %= 3

5. Increment and Decrement Operators
Used to increase or decrease a variable by 1.

Operator	Function	Example
++	Increment (pre/post)	++x or x++
--	Decrement (pre/post)	--x or x--

6. Conditional (Ternary) Operator
Shorthand for if-else:

cpp
Copy
Edit
int a = 10, b = 5;
int max = (a > b) ? a : b;  // If a > b, max = a, else max = b
8. Miscellaneous Operators
sizeof – Finds the size of a variable/type.
Example: sizeof(int)

& (Address of) – Returns memory address of a variable.

* (Dereference) – Used with pointers to access value.

:: (Scope Resolution) – Access global variables or class members.
