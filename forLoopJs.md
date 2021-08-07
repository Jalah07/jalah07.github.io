## JavaScript For Loop
- Loops are handy, if you want to run the same code over and over again, each time with a different value.
- The condition is checked before each iteration.
- `for (let i = 1; i <= 50; i++){
    console.log(i);
 } // Prints all the numbers 1 to 50.`
    1. ^ Beginning of the step is i = 1. Executes once upon entering the loop.
    2. Condition is i <= 50. Checked before every loop iteration. If false, the loop stops.
    3. Body is console.log(i); runs while the condition is truthy.
    4. The step is i++ and it executes after the body on each iteration.
- You can use `break` to escape the loop if you get caught in a infinite loop.

## While Loop
- The condition is checked before each iteration. The while loop loops through a block of code as long as a specified condition is true.
- `while (condition) {
  // code
  // so-called "loop body"
}`
- You can use `break/continue` to escape a while loop.

## Why are loops important?
- They help us simplify the task of repeating sets of instructions, which saves time. Loops allow you to shorten hundreds of lines of code to just a few lines of code. It makes your code is organized and manageable.
