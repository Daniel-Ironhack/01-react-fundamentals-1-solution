# React Click Counter

<br>

## Context

During this module, we learned about the state, how to access and update the state of a React `class` component and how to create event handlers in React.
In React, the state of a component is commonly updated as a response to a certain event, for example, on a mouse click. In this exercise, you will have a chance to check your understanding of these concepts.

<br>

## Getting Started

All your work should be done in the files `App.jsx` and `Counter.jsx` .
More specifically, **your task is to create a `Counter`** component and **render it** in the `App.jsx`.

Files `App.jsx` and `Counter.jsx` are already provided for you in the `/src` folder.

Files `App.jsx` and `src/index.js` already include the React app setup that you will need.

<br>

To begin working, you just need to start writing your code inside the `Counter.jsx` file.

When finished creating the component import the component in the `App.jsx` and render it where it is indicated by the comment `/* RENDER YOUR COMPONENT HERE */`.

<br>

## Task & Objectives

Once again, all your work should be done in the files `App.jsx` and `Counter.jsx`. All the tests can be found in the `__tests__/Counter.test.jsx` file.

Your task is to create a simple React component named `Counter`. The end goal will be to display the current value of the counter coming from the component `state`, and increment or decrement the counter by clicking on a corresponding button.

<br>

Here's a demo example of the working component:

![counter.gif](//res.cloudinary.com/strive/image/upload/w_1000,h_1000,c_limit/7212f45a413e7aea7091eab899efe386-counter.gif)

**Hint**: Make sure to also check the test results and the description provided in the **`Run Output`** section.

<br>
<hr>

### Task 1.1 - Create the `Counter` component:

⠀
In the file `Counter.jsx` create a new React component named `Counter`.
⠀
**_`Counter` component:_**

- should be a `class` component.
- should have a `state` starting with the initial value : `{ counter: 0 }`.
- in the `render` of the component:
  - it should have a `<button></button>` element, with a class name `"increment"`.
  - it should have a `<button></button>` element, with a class name `"decrement"`.
  - it should have a `<h1></h1>` element, showing the `counter` value from the `state`.
    _Initially when the `state` is `counter: 0` the `h1` element should display 0._
- should be rendered inside of the `App` component. _Do this step last, once you are done with the above steps._
  <br>

**Hint**: Remember to export your component once you are done creating it.

<br>
<hr>

### Task 1.2 - Implement `Counter` functionality:

⠀
Once done creating the `Counter` component, you should move on to implement the counter increment and decrement logic by adding the _on click_ event handler for each button.

Feel free to consult React's [documentation on handling events](https://reactjs.org/docs/handling-events.html) if you get stuck.
⠀
**_`Counter` component:_**

- should increment `counter` by 1 when the increment button is clicked, by updating the `counter` value in the `state`.
- should decrement `counter` by 1 when the decrement button is clicked, by updating the `counter` value in the `state`.

<br>

**Hint**: Make sure to also check the test results and the description provided in the **`Run Output`** section for additional details. Sometimes merely wrong spelling can lead to failing tests so make sure you always check the tests.

<br>

## Your code and submission

To check on your progress and if you are passing the tests, you can click on the **`RUN TESTS`** button.

In addition to this, you can reference the tests by opening the `Counter.test.jsx` file.

**_Reminder_**: You may want to reference the test output (in the `Run Output` panel) since there might be some edge cases stated in the tests, that might not be too obvious from the instructions.

<br>

#### Final Submission

While taking the challenge, you can check your progress multiple times via the **`RUN TESTS`** button.

To submit your work, you should click on the **`SUBMIT`** button. You will be asked to review your code and make a final submission. After you are done with the final submission you won't be able to resubmit your code again.

<br>

Good luck!

_Your Ironhack team_
