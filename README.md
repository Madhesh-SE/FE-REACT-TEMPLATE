Run this command after cloning the repo:

```js
npx husky-init && npm install && echo -e 'npx lint-staged' > .husky/pre-commit
```

The above command initializes husky and set the content of pre-commit file
