```jsx
// This file is named "Counter.jsx"

// SOLUTION FILE

import React from "react";

class Counter extends React.Component {
  constructor(props) {
    super(props);
    this.state = {
      counter: 0
    };
  }

  incrementCount = () => {
    this.setState((prevState) => ({ counter: prevState.counter + 1 }));
  };

  decrementCount = () => {
    this.setState((prevState) => ({ counter: prevState.counter - 1 }));
  };

  render() {
    return (
      <div>
        <h1>{this.state.counter}</h1>

        <button className='increment' onClick={this.incrementCount}>
          Increment
        </button>

        <button className='decrement' onClick={this.decrementCount}>
          Decrement
        </button>
      </div>
    );
  }
}

export default Counter;
```

---

```jsx
// This file is named "Counter.jsx"

// SOLUTION FILE
import React from "react";
import ReactDOM from "react-dom";
import Counter from "./Counter";

function App(props) {
  return (
    <div>
      <Counter />
    </div>
  );
}

export default App;
```
