# Cleaning Website Project

## Description of the Adventure
For this project, I created a simple website for my mom’s cleaning business. The goal was to build a clean and easy to use site that shows important information like services, pictures of cleaning work, and contact details. This project is meant to be something that can actually be used to help promote her business.

## Career Context
As a computer science major, I am interested in software development, especially frontend development. This project gave me hands on experience building a user friendly interface and working with modern tools like React and Vite. It also helped me understand how to build something for a real client, not just for a class assignment.

## Deliverable
- A homepage with a short introduction
- A services section with images
- A contact section with phone/email and service area
- A simple, clean layout that is easy to navigate

## Reflection

### Activity Description
I chose to make a functional website for my mom's cleaning company. I made a simple front end showing her service list and contact info. My mom wants to expand her business more, so this would help her do that.

### Technical or Professional Decisions
One important decision I made was to use React with Vite because it allows for fast development and a structured approach to building components. I also decided to keep the design simple and focused so that it would be easy for potential customers to use and understand.

### Contributions
I worked independently on this project. I handled the layout design, wrote the code, selected images, and set up the GitHub repository.

### Quality Assessment
I think the website meets the main requirements and provides a clean and functional layout. If I were to improve it, I would add features like online booking and better customization.

### Career Alignment
This project helped me close in on my career goals by giving me a real world development experience and it also taught me how to build something useful for an actual client which is important for all software engineering roles i have in the future.


























# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default defineConfig([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...

      // Remove tseslint.configs.recommended and replace with this
      tseslint.configs.recommendedTypeChecked,
      // Alternatively, use this for stricter rules
      tseslint.configs.strictTypeChecked,
      // Optionally, add this for stylistic rules
      tseslint.configs.stylisticTypeChecked,

      // Other configs...
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])
```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default defineConfig([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...
      // Enable lint rules for React
      reactX.configs['recommended-typescript'],
      // Enable lint rules for React DOM
      reactDom.configs.recommended,
    ],
    languageOptions: {
      parserOptions: {
        project: ['./tsconfig.node.json', './tsconfig.app.json'],
        tsconfigRootDir: import.meta.dirname,
      },
      // other options...
    },
  },
])
```
