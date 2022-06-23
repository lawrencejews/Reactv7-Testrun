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