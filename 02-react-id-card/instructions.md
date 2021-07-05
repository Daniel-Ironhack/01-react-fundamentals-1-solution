# React ID Card

<br>

## Context

We have learned how to create components in React and how to pass the props from the parent to the children's components. Now, let's test ourselves and see if we know how to re-create the example shown below.

<br>

## Getting Started

All your work should be done in the files `Container.jsx`, `IdCard.jsx` and `App.jsx`.
More specifically, **your task is to create components `Container`** and **`IdCard`** and **render them** in the `App.jsx`.

Files `Container.jsx`, `IdCard.jsx` and `App.jsx` are already provided for you in the `/src` folder.

Files `App.jsx` and `src/index.js` already include the React app setup that you will need.

<br>

To begin working, you just need to start writing your code inside the `Container.jsx` and `IdCard.jsx` respectively for each task.

When finished creating components, import them in the `App.jsx` and render them where indicated by the comment `/* RENDER YOUR COMPONENTS HERE */`.

<br>

## Tasks & Objectives

As stated above, your task is to create two React function components named `Container` and `IdCard`. The end goal will be to render these two components together in the `App.jsx` following the requirements of the tasks.

All the tests can be found in the `__tests__/Component.test.jsx` and `__tests__/IdCard.test.jsx` file.

Do not worry about the styles, the main point of the exercise is to create the components following the task requirements.

<br>

<hr>

### Task 1 - Create the `Container` component:

⠀
In the file `Container.jsx` create a new React component named `Container`.
This component must display its children elements/components passed between the opening and the closing tag of the component.

> **Hint**: Feel free to consult React's [documentation on passing children elements](https://reactjs.org/docs/composition-vs-inheritance.html) and the use of the [special `children` prop](https://reactjs.org/docs/glossary.html#propschildren) if you get stuck.

<br>

**Tasks** - **_`Container` component:_**

- should be a `function` component

- should display children elements, passed between the opening and closing tag of the component. _Example:_

  > ```html
  > <Container>
  >   <!--  CHILDREN ELEMENTS -->
  > </Container>
  > ```

<br>

<hr>

### Task 2 - Create the`IdCard` component:

⠀
In the file `IdCard.jsx` create a new React component named `IdCard`.
This component should receive 4 props ( `fullName`, `gender`, `birthday`, and `picture`) and display them.

<br>

**Tasks** - **_`IdCard` component:_**

- should be a `function` component

- in the `render` of the component:

  - it should have 3 `<p> </p> ` tags, each showing text for one prop:`fullName`, `gender`, `birthday`.

    > _When setting/passing `props` make sure to pass them by these exact names:_
    > _`fullName`, `gender`, `birthday`. Otherwise, the test won't pass_.

  - it should have an `<img />` with the image `src` value coming from the prop `picture`.

    > _When setting/passing the `props` for the image make sure to pass it by this exact name:_
    > _`picture`. Otherwise, the test won't pass_.

<br>

<hr>

### Task 3 - Render components `Container` and `IdCard` in App.jsx:

⠀
Once you are done creating the `Container` and `IdCard` components, the final task is to render them in the `App.jsx`.

Import the components in the `App.jsx` and render them where indicated by the comment `/* RENDER YOUR COMPONENTS HERE */`. For additional details see the Task requirements below.

<br>

**Tasks** -

- **_`Container` component:_**
  - should be rendered inside of the `App` component (`App.jsx`)

<br>

- **_`IdCard` component:_**

  - should be rendered inside of the App, between the opening and the closing tag of the <Container> </Container> component.
    You can use the below example snippet:

    > ```jsx
    > <Container>
    >   <IdCard
    >     fullName='John Doe'
    >     gender='male'
    >     birthday='1992-07-14'
    >     picture='https://randomuser.me/api/portraits/men/44.jpg'
    >   />
    >
    >   <IdCard
    >     fullName='Obrien Delores'
    >     gender='female'
    >     birth='1988-05-11'
    >     picture='https://randomuser.me/api/portraits/women/44.jpg'
    >   />
    > </Container>
    > ```

<br>

---

#### Example

```js
  <IdCard
    fullName='John Doe'
    gender='male'
    birthday="1992-07-14"
    picture="https://randomuser.me/api/portraits/men/44.jpg"
    />

  <IdCard
    fullName='Obrien Delores'
    gender='female'
    birth="1988-05-11"
    picture="https://randomuser.me/api/portraits/women/44.jpg"
    />
```

**Output**

![image](https://i.imgur.com/joAAtL7.png)

<br>

<br>

**Hint**: Make sure to also check the test results and the description provided in the **`Run Output`** section for additional details. Sometimes merely wrong spelling can lead to failing tests so make sure you always check the tests.

<br>

<hr>


## Your code and submission

To check on your progress and if you are passing the tests, you can click on the **`RUN TESTS`** button.

In addition to this, you can reference the tests by opening the files `Container.test.jsx` and `IdCard.jsx`.

**_Reminder_**: You may want to reference the test output (in the `Run Output` panel) since there might be some edge cases stated in the tests, that might not be too obvious from the instructions.

<br>

#### Final Submission

While taking the challenge, you can check your progress multiple times via the **`RUN TESTS`** button.

To submit your work, you should click on the **`SUBMIT`** button. You will be asked to review your code and make a final submission. After you are done with the final submission you won't be able to resubmit your code again.

<br>

Good luck!

_Your Ironhack team_
