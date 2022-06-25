## Intermediate React-v7
 - Component performance optimization: useMemo and useCallback for rendering when re-evaluation is needed.
 ### Tailwindcss
 - packages added `npm i -D tailwindcss@3.0.22 postcss@8.4.6 autoprefixer@10.4.2`
 - Add config file `npx tailwindcss init`
 - Add tailwind base, components and utilities to the styles file.
 - Add tailwindcss plugin for forms `npm i -D @tailwindcss/forms@0.4.0`
### Code-Splitting
- Lazy loading components dynamically using Suspense built into React-JS.
- This helps when dealing with large data files to be loaded in chunks.
### Server-Side-Rendering
- Loading small chunks of data as the page is loading for performance benefits.
- Seperate window rendering and Nodejs to Clientjs for DOM and Browser runtime.
- Set up your targets for Nodejs for frontend and backend.
- renderToNodeStream : streaming chunks of mark-up.
### Typescript
- Add dependencies `npm i -D typescript@4.5.5` for type check then add a tsconfig with `npx tsc --init`
- Select a target for your project plus jsx settings then add react types`npm i -D @types/react@17.0.39 @types/react-dom@17.0.11`
- ESlint should add typescript configuration `npm install -D eslint-import-resolver-typescript@2.5.0 @typescript-eslint/eslint-plugin@5.13.0 @typescript-eslint/parser@5.13.0` then add `ts and tsx` to the linter.
### Redux
- Add dependencies `npm i redux@4.1.2 react-redux`
- Dealing with state management i.e user types, call action, dispatch an action, insert action to root reducer, reducer delegates action, new state returned which becomes the store's state.
### Testing
- Adding dependencies `npm i -D jest@27.5.1 @testing-library/react@12.1.3` to work with react.
- Setting babel `npm i -D @babel/preset-env` for running tests in babelrc `@babel/preset-env` with a target of `node`
- Testing component with react helper library `npm i -D @testing-library/react-hooks@7.0.2`.
- Fetch testing `npm i -D jest-fetch-mock@3.0.3` then add `automock: false, setupFiles` to the package.json.
