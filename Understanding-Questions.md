# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
handler dispatches addOne action
addOne action returns ADD_ONE type
ADD_ONE case in the reducer adds 1 to the state.total
state.total gets passed down to TotalDisplay
rerender bc of state change

* 
...

* TotalDisplay shows the total plus 1.
