# Download Instagram



```js
// using https://websta.me/self/liked

fetch('https://websta.me/api/self/liked/', {credentials: 'include'}).then(x => x.json()).then(console.log, console.error)
```

you could also do oauth to get the instagram api
