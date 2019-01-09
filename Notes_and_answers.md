## Notes
- If stepping over something, for example a for loop, and it skips over them: That tells you the loop did nothing so effectively didn't run. Handy!
- You can hover over variables while debugging to get their value at the time of the pause. Without restarting the debugger, the changes to the code won't be noticed if those lines of code had already been run: Can rerun tests with the button in the top-left corner of the debugger window.
- Can put in multiple break points.


## Questions and Answers
### What is the purpose of a breakpoint?
It stops the application.

### Does the line of code on a breakpoint run when you start debugging?
No, it stops before executing the line on which the break is placed.

### How do we debug the next line of code?
Step through the lines of code. Use the Step Over.

### What does the step into command do?
Allows us to step in to a function on the line where it is currently paused, rather than running the whole line and function.

### What is the difference between evaluate expression and evaluate code fragment?
Used during the debugger pause.
Evaluate Expression: Evaluate and run some java code, run methods on the instances that have already been created. Basically a sandbox. Don't use semi-colons.
Code Fragment: Run multiple methods and multiple lines of code. Can start to create temporary variables to store things. So it's a little bit more developing than the evaluate expression. The variables only exist for as long as you are using the code fragment tool, and don't exist in the application itself. 
