1.  Name 3 JavaScript Array/Object Methods that do not produce side-effects?    map, filter, concat 
Which method do we use to create a new object while extending the properties of another object?
    Object.assign

1.  Describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
    Actions are objects and for the store that send data from your application to your store.
    Reducers are pure functions that copy state from actions instead of mutating state directly.  
    The Store holds global state for the application.

1.  What is the difference between Application state and Component state? When would be a good time to use one over the other?
    Application state (the Store) is accessable to any component. Application state can be useful in large scale applications. 
    Component state is local state, not accessable to other components. Component state can be useful in forms. 

1.  What is middleware?
    Functions that modify actions before they reach the reducers.

1.  Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
    Redux is synchronous by default. Redux-thunk allows Redux to be asynchronous, allowing our action-creators to handle asynchronous events.

1.  Which `react-redux` method links up our `components` with our `redux store`?
    .connect()