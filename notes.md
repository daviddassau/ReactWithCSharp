# Notes

```JavaScript
ReactDOM.render(<h1>Hello world</h1>,
document.getElementById('app'));
```
In these lines of code, `ReactDOM` is the name of a JavaScript library. This library contains several React-specific methods, all of which deal with the DOM in some way or another. The `.render` part is the most popular way to render JSX on the screen.

```ReactJS
var myList = (
	<ul>
    <li>David</li>
    <li>Thomas</li>
    <li>Dassau</li>
  </ul>
);

ReactDOM.render(myList,
document.getElementById('app'));
```
This code will create the variable `myList`, and the ReactDOM will then call that variable to print to the page.
