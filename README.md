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
