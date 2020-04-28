# Day 1: Notes to keep in mind
### Arithmetic Operators
* Addition, Subtraction, Division, Multiplications: +, -, /, *
* Exponentiation: 
  * 2 ** 3 // 8
  * 3 ** 2 // 9
  * 5 ** 4 // 625
* Increment (++)
  * Prefix (++operand) example (++a)
  * Postfix (operand++) (a++)

### What is the output of the following when we pass number 4.

```javascript    
 function main(input) {
    var a = input;
    // Print the value of 'a' and the preincremented value of 'a':
    console.log("a(" + a + "), ++a(" + ++a + ")");
    // Assign the current value of 'a' to 'b' and then postincrement 'a':
    var b = a++;
    // Print the values of 'a' once and 'b' twice, then postincrement the 2nd 'b':
    console.log("a(" + a + "), b(" + b + "), b++(" + b++ + ")");
    // Print the final values of 'a' and 'b':
    console.log("a(" + a + "), b(" + b + ")");
 }
 ```
 * Decrement (++)
  * Prefix (--operand) example (--a)
  * Postfix (operand--) (a--)
  
### What is the output of the following when we pass number 4.
 
```javascript 
function main(input) {
    var a = input;
    // Print the value of 'a' and the predecremented value of 'a':
    console.log("a(" + a + "), --a(" + --a + ")");
    // Assign the current value of 'a' to 'b' and then postdecrement 'a':
    var b = a--;
    // Print the values of 'a' once and 'b' twice, then postdecrement the 2nd 'b':
    console.log("a(" + a + "), b(" + b + "), b--(" + b-- + ")");
    // Print the final values of 'a' and 'b':
    console.log("a(" + a + "), b(" + b + ")");
}
 ```
