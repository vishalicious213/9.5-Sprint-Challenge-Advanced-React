- [ ] Why would you use class component over function components (removing hooks from the question)?

a) Prior to hooks, functional components could not natively make use of state. State had to be elevated to the parent component and then passed into the functional component via props.

b) Functional components also couldn't use lifecycle hooks, because they were extended from React.Component.


- [ ] Name three lifecycle methods and their purposes.

constructor()
Initializes local state in a class component (this.state)
Binds event handler methods to an instance (this.handleClick)

render()
Uses data in props or state and returns something (usually JSX) to the DOM to be rendered onscreen (functional component might not necessarily use state/props)

componentDidMount()
After elements on a page are rendered, this method provides a time during which updates from state (including API calls) can be rendered onscreen


- [ ] What is the purpose of a custom hook?

They allow the creation of reusable functions that can be shared between multiple components. Its more DRY and simplifies the code for the components that use them by removing duplicate logic.


- [ ] Why is it important to test our apps?

Testing reduces the risk of allowing bugs to make their way into production code. It also helps programmers to write stronger, more testable code, which helps with refactoring, documentation and puzzling out edge cases.
