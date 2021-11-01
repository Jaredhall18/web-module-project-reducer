# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* Dispatch the AddOne action through the handleChanges Event handler.
* The addOne Action calls the ADD_ONE Reducer
* The reducer adds 1 to the state.total and updates state
* App rerenders with total display component displaying updated state

* TotalDisplay shows the total plus 1.
