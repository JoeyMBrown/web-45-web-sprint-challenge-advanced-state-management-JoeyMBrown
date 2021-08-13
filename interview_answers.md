# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

    The context API helps prevent prop drilling.  It allows you to pass props throughout your entire application from one place, rather than having to pass props from parent to children dozens of times.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    store: A place to store all of your applications state.
    actions: Action creaters create Action objects that describe what needs to take place and get passed to our reducers.
    reducers: Reducers are functions that accept an action, and action type to understand how to update our state.

    The store is known as a 'single source of truth' in a redux application because it contains the state for our entire project.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

    Redux-thunk allows us to run async code within our action creators.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

    Redux.  The store combined with the  actions / reducers seems like a very powerful too.