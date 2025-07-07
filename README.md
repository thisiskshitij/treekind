# 🌱 TreeKind NGO Website

Official website for **TreeKind NGO**, a non-profit organization focused on reforestation and environmental awareness.

Built with **Next.js**, **TypeScript**, **Tailwind CSS**, and **Shadcn UI**, this project aims to deliver a performant, accessible, and engaging experience for visitors and donors.

---

## 🚀 Features

✅ **Fully Responsive & Accessible** — Mobile-first design with semantic HTML and accessible UI patterns.  
✅ **Modern Tech Stack** — Next.js, Vite, TypeScript, Tailwind CSS, Shadcn UI.  
✅ **Dynamic UI Components** — Reusable components for consistent, scalable design.  
✅ **Automated Testing** — End-to-end testing with Jest, Cypress, and Playwright.  
✅ **AI-Powered Chatbot** — Integrated OpenAI API to assist users and answer FAQs.  
✅ **Continuous Monitoring** — Deployed on Vercel, with error tracking via Sentry and performance checks using Lighthouse.  
✅ **Collaborative Design** — Built in close collaboration with non-technical stakeholders.

---

## 🛠️ Tech Stack

- **Framework:** Next.js, React, TypeScript
- **Styling:** Tailwind CSS, Shadcn UI
- **Bundler:** Vite
- **Testing:** Jest, Cypress, Playwright
- **Deployment:** Vercel
- **Monitoring:** Sentry, Lighthouse
- **AI:** OpenAI API

---

## 📦 Installation

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/treekind-ngo-website.git
   cd treekind-ngo-website


# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default tseslint.config([
  globalIgnores(['dist']),
  {
    files: ['**/*.{ts,tsx}'],
    extends: [
      // Other configs...

      // Remove tseslint.configs.recommended and replace with this
      ...tseslint.configs.recommendedTypeChecked,
      // Alternatively, use this for stricter rules
      ...tseslint.configs.strictTypeChecked,
      // Optionally, add this for stylistic rules
      ...tseslint.configs.stylisticTypeChecked,

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

export default tseslint.config([
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
