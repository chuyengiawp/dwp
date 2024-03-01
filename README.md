# Example
```javascript
const dwordpress = require('dwordpress')('url');
dwordpress('query', (posts, users) => {
  for (const post of posts) {
    const user = users[post.author];
  }
});
```
