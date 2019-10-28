1. What problem does the context API help solve?
   1. prop drilling
2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
   1. actions are objects that tell the reducer what to do and what data
   2. reducers are a function to immutably change state
   3. store is the state
3. What is the difference between Application state and Component state? When would be a good time to use one over the other?
   1. Application state is something that should be used amongst multiple components.  Component state is something that is only used in 1.  An example for component state would be for inputs
4. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?
   1. redux thunk allows for async actions.  If the action creator returns a function, we can send dispatch as a argument are dispatch actions asynchronously
5. What is your favorite state management system you've learned and this sprint? Please explain why!
   1. I love Context API the most.  It's lightweight and provides just enough functionality
