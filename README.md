Map and Filter 


map within return body
```js
users = [{name: dan}, {name: jeremy}, {name: amy}]

return (
  <div>
    {users.map((user) => (
      <div>
        {user.name}
    </div>
    ))}
  </div>
)

```

Map + Filter
```js


export default function App() {

numbers = [1,2,3,4,5]

const mapAndFilterData = () => {
let filteredMapData = numbers.filter((num) => num < 4 ).map((filtered) => filtered * 10);
}

  
  return (
    <div className="App">
      {users.map((mapAndFilterData) => (
        <div>
          {data}
        </div>
      ))}
    </div>
  );
}


```
