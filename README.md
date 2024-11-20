# React Review 3

## Instructions

### 1. Import a Component

Imagine you are writing code for a React project with a `components` directory.

The file and folder structure looks like this, with `App.jsx` inside the `src` folder,
and `Gallery.jsx` inside a `components` folder.
```
src
├── App.jsx
└── components
    └── Gallery.jsx
```

Inside `App.jsx` write the code that would import the `Gallery` component from `Gallery.jsx`

### 2. Object Destructuring

You have an object called `props`:

```js
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
```

Using object destructuring, extract the name, packaging, and temperature properites.

### 3. State in React

Describe the concept of state in React.

### 4. Using state in React

Inside the `Tea` component, add state that captures whether the Tea is currently brewing.
When the component is first rendered, the brewing state should be `true`. The `Tea` component 
does not need to render anything. Don't forget to import the appropriate functions from `"react"`.

### 5. Connect the handler

There is an unconnected handler called `checkTime` in the `Tea` component. Connect it to an
appropriate element inside the component.
