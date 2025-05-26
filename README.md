# 📝 Angular Task Manager App

A fully functional and responsive **Task Manager (To-Do List)** built using **Angular 9**, **TypeScript**, and **Angular Material**. This project is ideal for learning Angular best practices, modular architecture, component-based UI, and testing with Karma & Protractor.

---

## 📚 Overview

The **Angular Task Manager** is a lightweight, single-page application (SPA) that enables users to:

- Add new tasks
- Mark tasks as completed
- Delete tasks
- Filter tasks by status
- Manage their to-do items with an elegant, Material Design-based UI

It's a great starter project to understand Angular CLI projects, routing, forms, services, and component interaction. The app is organized with scalability and maintainability in mind.

---

## ✨ Key Features

- 🧠 **Component-based architecture**: Each part of the UI is encapsulated in reusable Angular components.
- 🗂️ **Modular folder structure**: Designed for scalability in larger applications.
- 💾 **Reactive Forms**: Efficient form handling for task creation and editing.
- 💅 **Angular Material UI**: Modern UI/UX out of the box.
- 📱 **Mobile responsive**: Optimized for various screen sizes.
- 🔍 **Live filtering**: Filter tasks by status (e.g., all, completed, active).
- 🧪 **Testing-ready**: Setup includes unit testing (Karma + Jasmine) and E2E (Protractor).
- ⚙️ **Linting and strict TS**: Clean code maintained via TSLint.

---

## 🛠️ Tech Stack

| Layer              | Tools Used                                    |
|-------------------|-----------------------------------------------|
| Frontend Framework| Angular 9.x (CLI generated)                   |
| Styling           | SCSS, Angular Material                        |
| Build Tool        | Angular CLI                                   |
| Testing (Unit)    | Karma, Jasmine                                |
| Testing (E2E)     | Protractor (can be migrated to Cypress)       |
| Linting           | TSLint                                        |
| Type Checking     | TypeScript                                    |

---

## 📁 Folder Structure

```
angular-todo-app/
├── e2e/                        # Protractor E2E tests
├── node_modules/               # Installed dependencies
├── src/
│   ├── app/                    # Angular components, modules
│   │   ├── task/               # Task list, item, form components
│   │   └── app.module.ts       # Root module
│   ├── assets/                 # Images, fonts, etc.
│   ├── environments/           # Environment configs
│   ├── index.html              # HTML shell
│   ├── main.ts                 # App entry point
│   ├── styles.scss             # Global styles
│   └── test.ts                 # Unit test setup
├── angular.json                # Angular CLI config
├── tsconfig.json               # TypeScript compiler config
├── tslint.json                 # Linting rules
└── package.json                # Dependencies and scripts
```

---

## 🧪 Running Tests

### ✅ Unit Tests
Run tests using Karma + Jasmine:
```bash
ng test
```

### ✅ E2E Tests
Run end-to-end tests using Protractor:
```bash
ng e2e
```

> _Note: Protractor is deprecated. For long-term use, consider Cypress or Playwright._

---

## ▶️ Getting Started

### 🔧 Prerequisites

- Node.js (>= 12.x)
- Angular CLI (v9.x recommended)
- Git

### 📦 Installation

```bash
# Clone the repo
git clone https://github.com/your-username/angular-todo-app.git
cd angular-todo-app

# Install dependencies
npm install

# Start dev server
ng serve
```

Open `http://localhost:4200` in your browser.

---

## 🚀 Build for Production

```bash
ng build --prod
```

Output will be located in `/dist/angular-todo-app`.

---

## 🧹 Lint the Code

```bash
ng lint
```

---

## 🌍 Deployment Options

- GitHub Pages
- Firebase Hosting
- Netlify
- Vercel
- Docker + NGINX

Let me know if you'd like setup instructions for any of these.

---

## 📄 License

This project is licensed under the MIT License.  
Feel free to use it for personal or commercial use.

---

## 🤝 Author & Contributions

Created by **Ambati Teja Sri Surya**.  
PRs and contributions are welcome. Please fork and open a pull request.
