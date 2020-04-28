## var
We use the var keyword to declare variables. 
The scope of a variable declared using this keyword is within the context wherever it was declared. 
For variables declared outside any function, this means they are globally available throughout the program. 
For variables declared within a function, this means they are only available within the function itself.

#### What is the output of the following when we pass 11

```javascript
function main(input) {
    var a = input;

    // If 'a' is odd:
    if (a % 2 == 1) {
        var a = input + 1;
        console.log("if(a): " + a);
    }

    console.log("main(a): " + a);
}
```
## let
We use the *let* keyword to declare variables that are **limited in scope to the block, statement, or expression in which they are used**. 
This is unlike the var keyword, which defines a variable globally or locally to an entire function regardless of block scope.

#### What is the output of the following when we pass 11

```javascript
function main(input) {
    let a = input;

    // If 'a' is odd:
    if (a % 2 == 1) {
        // Increment 'a' by 1
        let a = input + 1;
        console.log("if(a): " + a);
    }

    console.log("main(a): " + a);
}
```

## let
We use the const keyword to create a **read-only reference to a value**, meaning the value referenced by this variable cannot be reassigned. 
Because the value referenced by a constant variable **cannot be reassigned**. 
JavaScript requires that constant **variables always be initialized**.

```javascript
function main(input) {
    const a = input;

    // This will throw "SyntaxError: Missing initializer in const declaration"
    const b; 

    console.log(a);
}
```

### Source URL: https://www.hackerrank.com/challenges/js10-let-and-const/topics

