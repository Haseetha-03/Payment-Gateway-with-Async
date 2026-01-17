# React + Vite

This template offers a lightweight configuration for running React with Vite. It includes Hot Module Replacement (HMR) along with basic ESLint rules for better code quality.

At the moment, two official plugins are supported:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used with [rolldown-vite](https://vite.dev/guide/rolldown)) to enable Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) to provide Fast Refresh

## React Compiler

The React Compiler is disabled by default in this template because it can affect development and build performance. To enable it, refer to [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

For production-level applications, it is recommended to use TypeScript with type-aware ESLint rules enabled. Refer to the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for details on integrating TypeScript and [`typescript-eslint`](https://typescript-eslint.io) into your project.
