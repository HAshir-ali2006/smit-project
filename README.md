# smit-project
// P1: Check Even or Odd
function checkEvenOdd(num) {
  if (num % 2 === 0) {
    console.log("Even");
  } else {
    console.log("Odd");
  }
}

// P2: Calculate Square
function square(n) {
  return n * n;
}

// P3: Print Table of a Number
function printTable(n) {
  for (let i = 1; i <= 10; i++) {
    console.log(`${n} x ${i} = ${n * i}`);
  }
}

// P4: Find the Maximum of Two Numbers
function findMax(a, b) {
  return a > b ? a : b;
}

// P5: Check if Number is Positive, Negative, or Zero
function checkNumber(num) {
  if (num > 0) {
    console.log("Positive");
  } else if (num < 0) {
    console.log("Negative");
  } else {
    console.log("Zero");
  }
}
