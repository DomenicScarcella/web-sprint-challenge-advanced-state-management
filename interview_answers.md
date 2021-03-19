# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

    Context API allows global data to "skip generations" and get to the components that need it, without having to be inherited from components that don't need to use this specific data.


2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

    The store is the original state of the object, and is copied, rather than changed directly, whenever some state is altered.  This immutability, combined with the fact that store contains the entire application state in a single object, makes it a 'single source of truth.'

    Actions are objects that describe some change within the application state.

    Reducers are functions that take in the current state and an action, and mitigates any necessary state updates, finally returning the new copy of state.


3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

    The term "thunk" refers to a function that's returned by an earlier action-creator function.  Redux-thunk lets you run an asynchronus function, like an API call, by using middleware to intercept the data flowing from actions to reducers and doing something with the data before it gets to the reducer.  The action-creator can now be asynchronus.  


4. What is your favorite state management system you've learned and this sprint? Please explain why!

    I never been able to learn any language, even though I've tried many times over the decades.  JavaScript is a language, and as such, I don't understand JavaScript.  It's not really possible for me to have a favorite anything in a language I don't understand.