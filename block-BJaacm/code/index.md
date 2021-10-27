```js
let user = {
  name: 'Arya',
  sibling: ['Robb', 'Ryan', 'John'],
};
let allBrothers = ['Robb', 'Ryan', 'John'];
let brothersCopy = user.sibling;
let usename = user.name;
let newUser = user;
```

1. Memory representation

- Create the memory representation of the above snippet on notebook.
- Take a photo/screenshot and add it to the folder `code`

<!-- To add this image here use ![name](./hello.jpg) -->

2. Answer the following with reason:

- `user == newUser;` // true both are having same address
- `user === newUser;` // true both are having same address
- `user.name === newUser.name;` // true both are having same address
- `user.name == newUser.name;` // true both are having same address
- `user.sibling == newUser.sibling;` // true both are having same address
- `user.sibling === newUser.sibling;` // true both are having same address
- `user.sibling == allBrothers;` // false both are not having same address
- `user.sibling === allBrothers;` // false both are not having same address
- `brothersCopy === allBrothers;` // false both are not having same address
- `brothersCopy == allBrothers;` // false both are not having same address
- `brothersCopy == user.sibling;` // true both are having same address
- `brothersCopy === user.sibling;` // true both are having same address
- `brothersCopy[0] === user.sibling[0];` // true both are having same address
- `brothersCopy[1] === user.sibling[1];` // true both are having same address
- `user.sibling[1] === newUser.sibling[1];` // true both are having same address
