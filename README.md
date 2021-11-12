# REACT AND REDUX

# REDUX-LESSONS-INSTRUCTOR-ANDRES-R.-BUCHELI

## Take a look at the live example here:



## Usage:

## We can be more specific about the common steps involved in connecting Redux to a React UI:

* A render() function will be subscribed to the store to re-render the top-level React Component.
* The top-level React component will receive the current value of store.getState() as a prop and use that data to render the UI.
* Event listeners attached to React components will dispatch actions to the store.

## Take a look at store.js in the code editor. Here, you can see the completed light switch application following this pattern.

* The render() function is subscribed to the store.
* store.getState() is passed as a prop called state to the <LightSwitch /> component.
* The LightSwitch component displays the current state of the store, either 'on' or 'off', and adjusts the background colors accordingly.
* The LightSwitch component declares a click handler that dispatches a toggle() action to the store.
