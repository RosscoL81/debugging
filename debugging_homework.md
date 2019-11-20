# Introduction to Debugging in IDE

## Learning Objectives
- Know how to debug a Java application
- Understand breakpoints
- Understand the debugger console
- Know how to evaluate code fragments

## Task
As an introduction to debugging:
- watch the following video: [Intro to Debugging video](https://youtu.be/ErVZrVWZrko)


Answer the following questions:
1. What is the purpose of a breakpoint?
  - breakpoint pauses the application at a particular line of code where we want the debugger to start, launches the debugger console.

2. Does the line of code on a breakpoint run when you start debugging?
  - no, pauses before this line is ran.

3. How do we debug the next line of code?
  - Use the step-over button in console toolbar.

4. What does the step into command do?
  - step into switches the the method being called in the breakpoint line and pauses at the first line of that method.

5. What is the difference between evaluate expression and evaluate code fragment?
  - evaluate expression can run single line of code, call methods which have been created, no semi-colon required.
  - evaluate code fragment allows running multiple methods/lines of code and can set temporary variables.   needs semi-colons.
