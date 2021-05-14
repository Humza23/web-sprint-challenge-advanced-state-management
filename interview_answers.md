# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
Share props between components without prop drilling

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions are passed into the reducer function as an argument. When our reducer receives an action, it will update the state according to the type and payload on the action.

Reducers contain the initial state and are immutable since they return new objects

The store contains the application state and is therefore known as the single source of truth since all state is contained in it.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

redux-thunk allows us to use the dispatch function and run api calls inside our action creators.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

my favorite state management system I have learned this sprint is probably using class based components with prop drilling. The reason for this may be that method had a lot of time spent on it to allow me to feel more comfortable with it. I am also still trying to continue letting redux sit in my brain.