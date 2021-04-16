# next-typescript-starter
A starter for NextJS apps, including typescript (in strict mode), cypress for testing as well as Scss and @webpack/svgr for loading SVG files as React components.

## How to Use

- Create a new Next project using this starter by running the following command
```bash
npx create-next-app my-app -e https://github.com/Itope84/next-typescript-starter
cd my-app
```

- Edit the project `name` in package.json to your project name.

- Run the app
```bash
yarn dev
```

- Run cypress tests
```bash
yarn test
```

or to see the Cypress client:
```bash
yarn cypress
```

## Folder Structure
```
├── assets - (contains dynamic assets that would be imported into your components)
│   └─svgs (for holding SVG assets such as components)
├── cypress (contains cypress tests)
├── pages (Nextjs pages)
│   └── _app.tsx
│   └── index.tsx
├── styles
    └── components (for CSS modules)
    └── mixins (Sass mixins)
    └── base.scss
```

If you need something else that's not included, feel free to fork this repository and make your own modifications.

Cheers 🥂 
