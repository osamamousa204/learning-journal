# Comparison operators 

* A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality.



### The following table describes the comparison operators in terms of this sample code:

Operator                   | Description 
---------------------------|-------------------------------------------------------------------------------
Equal (==)                 | Returns true if the operands are equal.
---------------------------|-------------------------------------------------------------------------------
Not equal (!=)             | Returns true if the operands are not equal.
---------------------------|-------------------------------------------------------------------------------
Strict equal (===)         | Returns true if the operands are equal and of the same type. See also Object.
---------------------------|-------------------------------------------------------------------------------
Strict not equal (!==)     |	Returns true if the operands are of the same type but not equal, or are of different type.
---------------------------|-------------------------------------------------------------------------------
Greater than (>)           |	Returns true if the left operand is greater than the right operand.
---------------------------|-------------------------------------------------------------------------------
Greater than or equal (>=) |	Returns true if the left operand is greater than or equal to the right operand.
---------------------------|-------------------------------------------------------------------------------
Less than (<)              |	Returns true if the left operand is less than the right operand.	
---------------------------|-------------------------------------------------------------------------------
Less than or equal (<=)    |	Returns true if the left operand is less than or equal to the right operand.

## The While Loop
The while loop loops through a block of code as long as a specified condition is true.

### Syntax
while (condition) {
  // code block to be executed
}
### Example
In the following example, the code in the loop will run, over and over again, as long as a variable (i) is less than 10:

Example
while (i < 10) {
  text += "The number is " + i;
  i++;
}
## The For Loop
The for loop has the following syntax:

for (statement 1; statement 2; statement 3) {
  // code block to be executed
}
Statement 1 is executed (one time) before the execution of the code block.

Statement 2 defines the condition for executing the code block.

Statement 3 is executed (every time) after the code block has been executed.

### Example

for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}