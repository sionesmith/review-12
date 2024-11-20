# React Review 3

### 1. Import a Component

App.jsx

```jsx
// Write your code here

```

### 2. Object Destructuring

```jsx
const props = {
  name: 'English Breakfast',
  temperature: 99,
  type: 'Black Tea',
  origin: 'India',
  steepTime: 3, // in minutes
  caffeineContent: 40, // in mg per serving
  flavorNotes: ['Malty', 'Robust'],
  isOrganic: false,
  packaging: 'Tea Bags',
  price: 5.99, // in USD
  stockQuantity: 100,
  rating: 4.5, // out of 5
};

// Write your code here


```

### 3. State in React



### 4. Using state in React

```jsx


function Tea(props) {
  // Add your code here

}
```

Inside the `<Tea />` component, add state that captures whether the Tea is currently brewing.
When the component is first rendered, the brewing state should be `true`.

### 5. Connect the handler

There is an unconnected handler called `checkTime` in the `Tea` component. Connect it to an
appropriate element inside the component.

```jsx
import { useState } from "react";

function Tea(props) {
  const checkTime = () => { props.steepTime > props.startTime ? alert("TEA IS DONE!"); }

  return <>
    <h1>Tea Time</h1>
    <button>Check if tea is ready</button>
  </>
}
```
