# Interview Answers

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What are the main differences between a stateful and a functional component?
   functional components are simple functional component without having a local state but remember there is a hook in react to add state behavior in functional component as well
   Stateful component can contains the state object and event handling function, user actions as well

2. When does a componentWillMount function be called? What about a componentWillUpdate?
   componentWillMount is called before the render method is executed and componentWillUpdate is called right before the component renders and right after shouldComponentUpdate

3. Define stateful logic.
   Stateful logic is logic that is built into a component. It can be a function that handles a click event or maybe a function that sets toggle state, or even a function that formats data before it gets displayed.

4. What are the three step of creating a successful test? What is done in each phase?
   Arrange: We get te component needed for testing
   Act: We specify what should be in an element
   Assert: Then we most make sure the its true
