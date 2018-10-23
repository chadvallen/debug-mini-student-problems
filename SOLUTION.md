Problem:
increment function was not bound to the constructor

Where:
in Counter.js

Fix:
Change increment into an arrow function.
```
increment = () => {
    this.setState({ counter: this.state.counter + 1 });
  }
  ```