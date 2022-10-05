# ToDo App Created With React

[Mozilla Source Project](https://developer.mozilla.org/en-US/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_todo_list_beginning)

## React Interactivity and State

### Callback Functions to Handle Form Submission

We can't pass data from child to parent in the same way as we pass data from parent to child using standard props. Instead, we can write a function in <App /> that will expect some data from our form as an input, then pass that function to <Form /> as a prop. This function-as-a-prop is called a callback prop. Once we have our callback prop, we can call it inside <Form /> to send the right data to <App />.

### State and the useState Hook

Data which a component itself owns, is called state. State is another powerful tool for React because components not only own state, but can update it later. It's not possible to update the props a component receives; only to read them.

React provides a variety of special functions that allow us to provide new capabilities to components, like state. These functions are called hooks, and the useState hook, as its name implies, is precisely the one we need in order to give our component some state.

## nanoid

npm install nanoid

nanoid is a library that makes it easier to create unique identifiers
