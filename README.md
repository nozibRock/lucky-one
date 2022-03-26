# Lucky One Mart

Best online shopping for the luckyiest persons.

Created using React. 

## Live Site

link: 

### How React Works? 

React is a JavaScript library that creates user interfaces (UIs) in a predictable and efficient way using declarative code. It to helps build single page applications and mobile apps, or to build complex apps if we utilise it with other libraries. **React works in declarative code**.

### Difference between state and props? 

#### State

The state is an updatable structure that is used to contain data or information about the component and can change over time. A state must be kept as simple as possible. It represents the component's local state or information. It can only be accessed or modified inside the component or by the component directly.



| Props | State     |
| :---  |    :----:   | 
| Props are read-only.        |State changes can be asynchronous.|
| Props are immutable.        | State holds information about the components.|
|Props can be accessed by the child component. | State cannot be accessed by child components.|

#### Props

Props are read-only components. It is an object which stores the value of attributes of a tag and work similar to the HTML attributes. It allows passing data from one component to other components. It is similar to function arguments and can be passed to the component the same way as arguments passed in a function. Props are immutable so we cannot modify the props from inside the component.

### Explain how useState works?


useState is a Hook (function) that allows you to have state variables in functional components. You pass the initial state to this function and it returns a variable with the current state value (not necessarily the initial state) and another function to update this value.