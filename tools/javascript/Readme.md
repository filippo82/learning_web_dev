# Javascript

### Arrow functions

Before:
```javascript
hello = function() {
  return "Hello World!";
}
```
After:
```javascript
hello = () => {
  return "Hello World!";
}
```

### Children in JSX
In JSX expressions that contain both an opening tag and a closing tag,
the content between those tags is passed as a special prop: `props.children`.

### Destructuring the props
When you write a component like
```javascript
const Link = ({ active, children, onClick }) => { ... }
```
You are destructuring the props and getting only `active`, `children`, and `onClick` from the props passed to the component.


