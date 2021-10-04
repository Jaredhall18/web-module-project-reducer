# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code executes for each step.
* The user presses the 1 button.
* CAlls our event handler function
*event handler dispatches the the addOne action
*addOne action returns the Case type ADD-One
*reducer case type ADD_One returns the current State + 1
...

* TotalDisplay shows the total plus 1.
