# usetoggle-react - [Demo](https://codesandbox.io/s/usetoggle-4lluw?file=/src/App.js)

Toggle custom hook for react

### example useage

```
const [isVisble, toggle] = useToggle(false);
<button onClick={toggle}>{isVisble ? "Close" : "Open"}</button>
{ isVisble && <div>Element</div> }
```
