# Curricula
A collection of patterns and practices that help you build better React components

Follow these codesandboxes for the workshop:

### Component Design
In this first part we will go through some basic patterns that can be applied on regular React components to make them more readable and to allow you to write less code for the same result.

**[Sandbox link](https://codesandbox.io/s/oqx6jkvwn5)**

As a bonus, we will have a quick look at the difference between stateless components and the **PureComponent** class from React. [Sandbox link](https://codesandbox.io/s/03k2xzo3zl).

### Having fun with Props
Now we will tackle various patterns of passing props from one component to another. As applications grow, so does the need of passing values between multiple level of components.

**[Sandbox link](https://codesandbox.io/s/3qn5yz1pkq)**

### Composition and Reusability
Now it's time to look at some patterns aimed at ensuring we have code and functionality reusability across an entire app as well as making communication between components in different parts of the application easier.

* **Higher Order Components** - [Sandbox link](https://codesandbox.io/s/4wk0rv72z7)
* **Render Props** - [Sandbox link](https://codesandbox.io/s/1824x2jnjj)
* **React Context** - [Sandbox link](https://codesandbox.io/s/v3q2olyxv7)
* **BONUS - React Hooks** - [Sandbox link](https://codesandbox.io/s/7ml4on34kx)

### Final Exercise
At the end of the workshop, it's time to put everything we learned to practice. HOCs, RenderProps, React Context and all the rest, bundled into a single task, of implementing your own state management system.

We'll start from **[this sandbox](https://codesandbox.io/s/n320rp4x2p)** and we will have to:
* Implement a **simple store** object (nothing fancy)
* **Provide** the store reference to all the React components via React Context
* Create a connect **HOC** which can **consume** the store
* Implement a couple of connect calls with their corresponding mapStateToProps, mapDispatchToProps.

## References

* [My Original Article](https://medium.freecodecamp.org/evolving-patterns-in-react-116140e5fe8f)
* [React Children Explained](https://mxstbr.blog/2017/02/react-children-deepdive/)
* [React Patterns Course on Egghead](https://egghead.io/courses/advanced-react-component-patterns)
* [Ryan Florence - Compound Components](https://www.youtube.com/watch?v=hEGg-3pIHlE)
* [Michael Jackson - Never write another HOC](https://www.youtube.com/watch?v=BcVAq3YFiuc)
* [React Context API](https://medium.com/dailyjs/reacts-%EF%B8%8F-new-context-api-70c9fe01596b)

LIVE SESSION: https://codesandbox.io/live/qLgQ3
