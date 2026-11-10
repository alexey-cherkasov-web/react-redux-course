# React & Redux Course

Practice projects from an online React course on Udemy. I went through the course lesson by lesson, from plain JavaScript to Redux. Every folder is a small, self-contained app.

> This is a learning repository, not a production project. For a larger project of mine, see [friends-events-react](https://github.com/Alekseytcherkasoff/friends-events-react) (React + PHP JSON API).

## What is covered

### Part 1: React basics

| Lesson | Topic |
|---|---|
| [01-vanilla-js](part-1/01-vanilla-js) | Starting point: a UI in plain JavaScript |
| [02-react-hello-world](part-1/02-react-hello-world) | The first React component |
| [03-react-vs-vanilla-js](part-1/03-react-vs-vanilla-js) | The same UI in React and in vanilla JS, side by side |
| [04-jsx-hello-world](part-1/04-jsx-hello-world) | JSX syntax |
| [05-react-JSX-green-button](part-1/05-react-JSX-green-button) | A button component written in JSX |
| [06-create-react-app](part-1/06-create-react-app) | A project bootstrapped with Create React App |
| [07-create-react-app-eject](part-1/07-create-react-app-eject) | Ejecting Create React App to see the build configuration |
| [08-reusable-components](part-1/08-reusable-components) | Building reusable components |

### Part 2: Props and state

| Lesson | Topic |
|---|---|
| [09-props](part-2/09-props) | Passing data to components with props |
| [10-conditional-rendering](part-2/10-conditional-rendering) | Conditional rendering |
| [11-state](part-2/11-state) | Component state |
| [12-state-via-props](part-2/12-state-via-props) | Passing state and handlers down through props |
| [13-map](part-2/13-map) | Rendering lists with `map()` |

### Part 3: Lists, forms and composition

| Lesson | Topic |
|---|---|
| [14-map-array-of-objects](part-3/14-map-array-of-objects) | Rendering a list from an array of objects |
| [15-logical-and-operator](part-3/15-logical-and-operator) | Conditional rendering with the `&&` operator |
| [16-react-fragment](part-3/16-react-fragment) | React Fragments |
| [17-uncontrolled-input](part-3/17-uncontrolled-input) | Uncontrolled inputs |
| [18-controlled-input](part-3/18-controlled-input) | Controlled inputs |
| [19-children-prop](part-3/19-children-prop) | The `children` prop |

### Part 4: Effects, data and styling

| Lesson | Topic |
|---|---|
| [20-useEffect](part-4/20-useEffect) | The `useEffect` hook |
| [21-jsonplaceholder-posts](part-4/21-jsonplaceholder-posts) | Loading posts from the JSONPlaceholder API |
| [22-useeffect-async-await](part-4/22-useeffect-async-await) | Using `async/await` inside `useEffect` |
| [23-css-modules](part-4/23-css-modules) | Scoped styles with CSS Modules |
| [24-todo-app-v1](part-4/24-todo-app-v1) | A to-do app (first version) |

### Part 5: Routing and state management

| Lesson | Topic |
|---|---|
| [26-react-router](part-5/26-react-router) | Client-side routing with React Router |
| [27-context-api](part-5/27-context-api) | The Context API |
| [28-reducer](part-5/28-reducer) | Reducers (`useReducer`) |
| [29-pure-redux](part-5/29-pure-redux) | Redux on its own, without React bindings |
| [30-react-redux](part-5/30-react-redux) | Redux connected to React with `react-redux` |
| [99-template](part-5/99-template) | A starter template for new lessons |

## Technologies

JavaScript (ES6+), React, JSX, React Hooks, CSS Modules, React Router, Context API, Redux, react-redux, Create React App

## How to run a lesson

Every lesson is an independent project with its own `package.json`:

```bash
cd part-4/20-useEffect
npm install
npm start
```

Check the `scripts` section of the lesson's `package.json`: Create React App projects start with `npm start`, Vite projects with `npm run dev`. You need a recent LTS version of Node.js.
