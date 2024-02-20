### Conceptual Exercise

Answer the following questions below:

- What is React? When and why would you use it?
React serves as a JavaScript library for constructing user interfaces, particularly handy for crafting interactive UI components within web applications.

- What is Babel?

Babel functions as a JavaScript compiler that transforms ECMAScript 2015+ (ES6+) code into a version compatible with older JavaScript environments.

- What is JSX?

JSX (JavaScript XML) operates as a syntactic extension for JavaScript, enabling the authoring of HTML-like code within JavaScript files, commonly employed in React to define UI structure.

- How is a Component created in React?

A React component is established by defining a JavaScript function or class that either extends React.Component or utilizes hooks such as React.useState or React.useEffect.

- What are some difference between state and props?

State represents mutable data specific to a component, subject to change, while props denote immutable data passed from a parent component to a child component.

- What does "downward data flow" refer to in React?

"Downward data flow" signifies the practice of transferring data from parent components to child components via props, ensuring a unidirectional data flow within React applications.

- What is a controlled component?

A controlled component refers to a form element whose value is managed by React state, ensuring that changes to the value trigger re-renders of the component.

- What is an uncontrolled component?

An uncontrolled component refers to a form element whose value is not directly managed by React state but instead by the DOM itself.

- What is the purpose of the `key` prop when rendering a list of components?

The key prop is employed when rendering a list of components to facilitate React in identifying changes, additions, or removals within the list.

- Why is using an array index a poor choice for a `key` prop when rendering a list of components?

Utilizing an array index as a key prop when rendering a list of components is discouraged due to potential issues with component reordering and reconciliation.

- Describe useEffect.  What use cases is it used for in React components?

useEffect functions as a hook in React, allowing for the execution of side effects within functional components after rendering.

- What does useRef do?  Does a change to a ref value cause a rerender of a component?

useRef serves as a hook in React that creates a mutable object whose current property can hold references to DOM elements or values, without triggering re-renders upon changes.

- When would you use a ref? When wouldn't you use one?

You'd employ a ref in React when direct access or manipulation of a DOM element is necessary, or when maintaining a mutable value across renders without causing component re-renders.

- What is a custom hook in React? When would you want to write one?

A custom hook in React is a JavaScript function prefixed with "use" that can encapsulate and reuse logic across multiple components, promoting code reusability and organization within React applications.
