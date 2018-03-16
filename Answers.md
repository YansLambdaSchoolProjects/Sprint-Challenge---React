# Answers

1. What is React JS? How does it differ from other JavaScript frameworks?
React JS is a front end frame work for building user interfaces. It's different from other frameworks because it combines separation of concerns. The best practice for creating react apps is to utilize components and use JSX. JSX combines HTML syntax in JavaScript code to create components. Before react separation of concerns was the best practice. This separation of concerns involves keeping logic (JS), style (CSS), and structure (HTML) in separate files when developing an application.

2. Explain briefly the React Component Lifecycle. Name three of the methods that are a part of the lifecycle and what they do.

The component lifecycle is the process each component goes by automatically calling methods and passing in that data at certain points. Three methods are shouldUpdate(), which initializes the data and sets it so that it will be able to call the willUpdate() at a point in the near future when the component receives new data that makes changes to the virtual DOM. When the render() method is called that method causes the component to update which automatically triggers the didUpdate() method upon completion. Other lifecycle methods keep track of properties or whether or not the component has been mounted or unmounted.

3. Briefly describe some of the differences between a Class/Stateful component and a Functional/Presentational component.

A stateful component is a component that has its data changed. For example, a counter is a stateful component because it keeps track of the state (value) of the component and updates when conditions are met. 

A presentational component does not keep track of values and just renders on the page and does not change.