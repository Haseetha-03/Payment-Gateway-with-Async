# React + Vite

This template offers a simple and efficient way to run React with Vite. It supports Hot Module Replacement (HMR) and includes basic ESLint rules to help maintain clean and consistent code.
- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

TThe React Compiler is disabled by default in this template because it can impact development and build performance. If you want to enable it, refer to the official React documentation for setup instructions.[this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration
 
 When building a production-ready application, it is recommended to use TypeScript with type-aware linting rules. 
 Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.