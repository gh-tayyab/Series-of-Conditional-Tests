# Series-of-Conditional-Tests


Question: Conditional Tests: Write a series of conditional tests. Print a statement
describing each test and your prediction for the results of each test. Your code
should look something like this:
• Look closely at your results, and make sure you understand why each line evaluates to True or False.
• Create at least 10 tests. Have at least 5 tests evaluate to True and another 5 tests evaluate to False.

let x=3;
let y=4;
// Test 1
console.log("Is x is smaller than y? I predicted True");
console.log(x<y)

// Test 2
console.log("Is x is greator than y? I predicted False");
console.log(x>y);

// Test 3
console.log("Is x is less than equal to y? I predicted True");
console.log(x<=y);

// Test 4
console.log("Is x is greator than equal to y? I predicted False");
console.log(x>=y)

// Test 5
console.log("Is x is not equal to y? I predicted True");
console.log(x!=y);

// Test 6
console.log("Is x is equals to  y? I predicted False");
console.log(x==y)

// Test 7
console.log("Is x is equal equals to  y? I predicted False");
console.log(x===y)

// Test 8
console.log("Is x is equals to 3 &  y is equals to 4? I predicted True");
console.log(x==3 && y==4)

// Test 9
console.log("Is x is equals to 3 &  y is equals to 4? I predicted False");
console.log(x==3 && y==5)

// Test 10
console.log("Is x is equals to 3 &  y is equals to 4? I predicted True");
console.log(x==3 || y==4)
