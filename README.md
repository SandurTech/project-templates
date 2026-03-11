![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=flat&logo=vite&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB) ![Sass](https://img.shields.io/badge/Sass-CC6699?style=flat&logo=sass&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![TS](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

---

# 🛠️ Project Templates

A centralized collection of production-ready project boilerplates and standardized folder structures. This repository is designed to eliminate repetitive setup time and enforce consistent architectural patterns across different stacks.

---

## 📖 About the Project

I started this project after repeatedly facing the same overhead when starting new applications. Whether it was a portfolio, a side project, or a quick prototype, I found myself manually configuring Vite, setting up SCSS modules, and organizing the same folder hierarchies over and over.

This repository serves as my "Source of Truth." It’s built for myself and any developers or teams who value jumping straight into the core logic of an app without wrestling with initial configuration.

---

## 🧩 Available Templates

### 1. Vite + React + SCSS 

Folder: ```/vite-react-scss```

The primary boilerplate for modern React applications, focusing on a layout-first architecture.

* **Modular Styling**: Implements **SCSS Modules** for locally scoped styling and namespace isolation.
* **Design System**: Centralized `_variables.scss` and `_mixins.scss` for theme consistency and rapid UI development.
* **Layered Architecture**: Explicit directory separation for `layouts`, `sections`, `components`, and `data`.
* **Optimized Tooling**: Pre-configured with **Vite** for fast HMR and optimized production builds.

### 2. Vite + React + TypeScript + SCSS

Folder: ```/vite-react-ts-scss```

A type-safe version of our primary boilerplate, combining React and SCSS Modules with TypeScript for enhanced developer experience.

* **TypeScript Support**: Full type safety for components, hooks, and props, ensuring robust and maintainable code.
* **Modular Styling**: Implements **SCSS Modules** for locally scoped styling and namespace isolation.
* **Design System**: Centralized `_variables.scss` and `_mixins.scss` for theme consistency and rapid UI development.
* **Layered Architecture**: Explicit directory separation for `layouts`, `sections`, `components`, and `data`.
* **Optimized Tooling**: Pre-configured with **Vite** and TypeScript-specific ESLint rules.

_More templates are coming soon! ✨_

---

## 🏗️ Technical Architecture

This repository follows the **Clean Architecture** principles to ensure modularity and ease of maintenance:

1. **Separation of Concerns**: UI components are decoupled from structural layouts and global styles.
2. **Scalability**: Built to handle growth from simple prototypes to complex multi-page applications.
3. **Standardized Config**: Includes optimized `.gitignore`, `eslint.config.js`, and `vite.config.js` defaults.

---

## 🛠️ Usage

### Quick Start (using Degit)

To pull a specific template without the entire repository history:

```bash
npx degit amogharajsandur/project-templates/vite-react-scss your-app-name
```

Manual Installation:

* Navigate to the template folder: `cd your-app-name`
* Install dependencies: `npm install`
* Start dev server: `npm run dev`