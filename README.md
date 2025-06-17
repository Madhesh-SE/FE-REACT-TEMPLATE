## Run this command after cloning the repo:

```js
npx husky-init && npm install && echo -e 'npx lint-staged' > .husky/pre-commit
```

The above command initializes husky and set the content of pre-commit file

## Folder Structure of "src"

```text
src
├── assets
│   ├── icons - Svgs, Svgs as React Components
│   └── images - Png, Jpg, Jpeg format images
├── components
│   ├── charts - BarChart, LineChart, PieChart etc...
│   ├── commons - Components common to this project
│   └── core - Components common to all the projects
├── designSystem - Any utility classes, colors, typography, fonts, mixins etc...
├── hooks - Common hooks
├── pages - Contains layout, components corresponding to each route
├── routes - Route configs, routing logic
├── state - State management logic
└── utils - Common utilities
```