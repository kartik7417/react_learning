# Learning - React & Vite Project

A modern React web application built with Vite, Bootstrap, and React Router. This project demonstrates core React concepts including component management, routing, form handling, and state management.

## 🎯 Project Overview

**Learning** is a comprehensive React application that showcases:
- React component architecture and reusable components
- Client-side routing with React Router
- Form handling with state management
- Bootstrap integration for responsive UI
- Counter and table generation examples

## 📋 Features

- **Home Page**: Landing page with navigation
- **Counter**: Interactive counter component with increment/decrement functionality
- **Table Generator**: Dynamic multiplication table generator
- **Form Handling**: Complete form with validation, multiple input types, and data display
- **Responsive Navigation**: Bootstrap navbar with active link styling
- **Footer**: Copyright section with branding

## 🛠️ Tech Stack

- **React** 18.2.0 - UI library
- **Vite** 5.2.0 - Build tool and dev server
- **React Router DOM** 7.8.2 - Client-side routing
- **Bootstrap** 5.3.7 - CSS framework
- **ESLint** 8.57.0 - Code linting

## 🚀 Quick Start

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
cd d:\WEB-VP\Learning

# Install dependencies
npm install

# Start development server
npm run dev
```

The app will be available at `http://localhost:5173`

### Build for Production

```bash
npm run build
```

Output files will be in the `dist/` directory.

### Preview Production Build

```bash
npm run preview
```

### Linting

```bash
npm run lint
```

## 📁 Project Structure

```
Learning/
├── src/
│   ├── components/
│   │   ├── Header.jsx          # Navigation bar with routes
│   │   ├── Home.jsx            # Home page component
│   │   ├── Counter.jsx         # Counter component (presentational)
│   │   ├── Counter3.jsx        # Alternative counter implementation
│   │   ├── Table.jsx           # Multiplication table generator
│   │   ├── TableOf.jsx         # Alternative table implementation
│   │   ├── FormHandling.jsx    # Form with validation and data display
│   │   ├── Footer.jsx          # Footer component
│   │   └── Body.jsx            # Body layout component
│   ├── App.jsx                 # Main app with routing setup
│   ├── main.jsx                # React entry point
│   ├── App.css                 # Global styles
│   ├── index.css               # Base styles
│   ├── assets/                 # Static assets
│   └── oldapp/                 # Legacy app versions (archived)
├── public/                     # Public static files
├── index.html                  # HTML entry point
├── vite.config.js              # Vite configuration
├── package.json                # Dependencies and scripts
├── .eslintrc.cjs               # ESLint configuration
└── .gitignore                  # Git ignore rules
```

## 📝 Component Details

### Header Component
Navigation bar using React Router's `NavLink` with active state styling (red and bold for active routes).

### Counter Component
Accepts `count` prop and `onIncrement`/`onDecrement` callbacks. Displays count in yellow, turns red when zero.

### FormHandling Component
Complex form with:
- Text input (name)
- Email input
- Number input (age)
- Radio buttons (gender selection)
- Checkboxes (skill selection)
- Dropdown select (department)
- Confirmation checkbox
- Dynamic table displaying submitted records

### Table Component
Generates a multiplication table for a given number (default: 4) displaying products 1-10.

## 🔄 Available Scripts

| Command | Description |
|---------|-------------|
| `npm run dev` | Start Vite dev server with HMR |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint checks |

## ⚙️ Configuration

### ESLint Rules
The project uses ESLint with React-specific rules. See `.eslintrc.cjs` for details.

### Vite Configuration
Default Vite setup with React plugin enabled. See `vite.config.js`.

## 🐛 Known Issues

- 3 moderate npm vulnerabilities detected. Run `npm audit fix` to address.
- Some deprecated packages included (inflight, rimraf, glob, eslint). Consider updating.

## 📦 Dependencies

### Production
- react: ^18.2.0
- react-dom: ^18.2.0
- react-router-dom: ^7.8.2
- bootstrap: ^5.3.7

### Development
- @vitejs/plugin-react: ^4.2.1
- vite: ^5.2.0
- eslint: ^8.57.0
- And related type definitions and plugins

## 🚀 Deployment

Build the project and deploy the `dist/` folder to your hosting provider:

```bash
npm run build
# Deploy dist/ folder to your host
```

## 📄 License

See LICENSE file in the root directory.

## 👨‍💻 Author

**Divyanshu1404** - [GitHub](https://github.com/Divyanshu1404)

## 🤝 Contributing

Feel free to fork, modify, and submit pull requests to improve this project.
