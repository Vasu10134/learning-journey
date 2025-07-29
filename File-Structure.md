<h1>📁 File Structure Overview (Tabular Format)</h1>

| File/Folder            | Description                                               |
|------------------------|-----------------------------------------------------------|
| 📁 node_modules/        | Auto-installed packages (DO NOT TOUCH ❌)                 |
| 📁 public/              | Static files (favicon, robots.txt, etc.)                 |
| └── index.html         | Main HTML file (entry point)                              |
| 📁 src/                 | 🚨 90% of your dev time here!                             |
| ├── 📁 assets/          | Images, fonts, icons, etc.                                |
| ├── 📁 components/      | Reusable UI components (Button, Navbar, etc.)            |
| ├── 📁 pages/           | App screens (Home, Login, Dashboard)                     |
| ├── 📁 hooks/           | Custom React hooks (useDarkMode, etc.)                   |
| ├── 📁 utils/           | Helper functions (formatDate, slugify)                   |
| ├── 📁 styles/          | Global CSS or Tailwind layers                            |
| ├── App.tsx            | Root component                                            |
| ├── main.tsx           | React entry file → hooks into `index.html`               |
| └── components.json    | Optional: Component registry or config                   |
| .gitignore             | Git exclusion rules                                       |
| bun.lockb              | 🔒 Lockfile for Bun package manager                      |
| eslint.config.js       | ESLint rules for clean code                               |
| package.json           | Declares dependencies, scripts, etc.                      |
| package-lock.json      | Lock file (for npm consistency)                           |
| postcss.config.js      | Required for Tailwind to work                             |
| tailwind.config.ts     | Tailwind customizations (colors, fonts, etc.)             |
| tsconfig.json          | Global TypeScript settings                                |
| tsconfig.app.json      | TypeScript for React app (more specific)                  |
| tsconfig.node.json     | TypeScript for backend/node-specific stuff                |
| vite.config.ts         | Vite bundler settings (aliases, plugins)                  |
