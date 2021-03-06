# Class Component State & Life Cycle: Assessment

## Brief

The objective of this assessment aims to complement the practical exercises you have done in lesson and assignment. In the lesson, you have faced certain complex syntax such as `this`, `.bind()` and `{}` in JSX. Let's dive a little more to understand what are these all about. Let the questions in this assessment guide you through your research.

### Question 1

Why do we have to prefix function with `this.` (Example: `this.functionName`) within a class component when we reference a function from another function?

```
Binding 'this' to the class method enables us to access props and state for the component with this.props and this.state.
```

### Question 2

Qn 2.1 - Explain in your own words what does `this.functionA = this.functionA.bind(this);` do.

```
functionA belongs to the method functionA().
We would need to bind react component 'this' to the method so as to allow usage of this.state and this.props in the method.
```

Qn 2.2 - Why do you have to write `this.functionA = this.functionA.bind(this);` in constructor?

```
It is best practice to write it in the constructor.
I would want to avoid function creation inside render.   
```

### Question 3

In HTML, we write an inline style with `<div style="background-color:red">` while in React, we write it as `<div style={{backgroundColor:'red'}}>`. Give an explanation on the differences in your own words.

```
In React, inline CSS is written in JavaScript object. If we write as background-color, JavaScript will read it as 2 strings, hence we will need to combine as backgroundColor.
Also, in JSX, both JavaScript expression and JavaScript object are written inside curly braces.
```

## Submission Guidelines

- Cite any relevant sources consulted during your research
- Solve the problems using your own code
- Do not copy and paste solutions from the source material
- Submit your assignment to black board.
