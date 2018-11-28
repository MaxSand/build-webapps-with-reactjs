If a component is written as a Javascript function, and then rewritten as a Javascript class, the return value of its `render` function should be:

the elements that the component should render
exactly the same as the return value of the component when it was written as a function

___________________________________________________________________
Component `props` are:

read-only.
passed in when the component is called.

___________________________________________________________________
The right place for code meant to run during a component's initialization is:

in the constructor function.

___________________________________________________________________
Calling `super()` in the constructor function of a React component will:

run the constructor function of the React.Component class.

___________________________________________________________________
If two or more components need to share access to a single element of state, the right place to locate that state is:

in a common ancestor component.

___________________________________________________________________
How can we make sure that events in a child component trigger appropriate changes in a parent component's state?

With a callback that was passed in as a prop from the parent.

___________________________________________________________________