## Assignment operators
- = equals sign. Ex: a = b
- +=  plus equals. Ex: a += b
- -= minus equals. Ex: a -= b
- *= times equals. Ex: a *= b
- /= divide equals. Ex: a /= b
- %= modulo equals. Ex: a *= b

## Comparison operators
- == Equal to
- === Strict equal to. Have to be equal to and same type.
- != 	Not equal to
- !== Strict not equal value or not equal type.
- > Greater than.
- >= Greater than or equal to.
- < Less than.
- <= Less than or equal to.

## Arithmetic operators
- % Remainder
- + Additon
- - Subtraction
- * Multiplication
- ** Exponentiation
- / Division
- ++ 	Increment
- -- Decrement

## Conditional operator
- condition ? val1 : val2 **Ex: const canDrink = (age >= 21) ? true : false;**

## Functions
- A JavaScript function is a block of code designed to perform a particular task. They allow the code to be called many times without repetition.

- A JavaScript function is executed when "something" invokes it (calls it).

- A function may access outer variables. But it works only from inside out. The code outside of the function doesn’t see its local variables.

`function areaSquare(number) {
    return number*number;
}`

## Naming a function

- Try to make the name with verb. It should be brief and accurate as possible what the function does.
  - "get…" – return a value,
  - "calc…" – calculate something,
  - "create…" – create something,
  - "check…" – check something and return a boolean, etc.
