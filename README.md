<<<<<<< HEAD
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
=======
# React Task Tracker

## Project Overview

This project is a simple task tracker built with React. It allows users to add, complete, delete, and filter tasks. Tasks persist using browser localStorage.

This project demonstrates core front-end engineering skills including:

• React state management  
• Component rendering  
• Event handling  
• Immutable updates  
• Local storage persistence  
• UI filtering logic  

---
## Engineering Considerations

Key design decisions:

State isolation improves maintainability.

Immutable updates prevent rendering bugs.

Local storage chosen instead of backend due to project scope.

Filtering handled through derived state instead of modifying original data.

Component simplicity prioritized over premature optimization.
## Features

• Add tasks  
• Delete tasks  
• Mark tasks complete  
• Filter All / Active / Completed  
• Data persistence using localStorage  
• Clean responsive layout  

---

## Technologies Used

React  
JavaScript  
Vite  
CSS  
localStorage API  

---

## Architecture Decisions

### Why React
React allows component-based UI development and clear state management.

### Why useState
Used to manage:
- task input
- task list
- filter state

### Why useEffect
Used to:
- synchronize tasks with localStorage
- persist user data

### Why task objects instead of strings

Tasks are structured like:

npm install
Start development server:

npm run dev

Open:
http://localhost:5173


---
## Project Structure
src/
  App.jsx
  App.css
  main.jsx

assets/
  screenshot.png

README.md
package.json

## Future Improvements

Potential enhancements:

• Edit task feature  
• Task priorities  
• Due dates  
• Dark mode  
• Drag and drop ordering  
• Backend API integration  

---

## Application Screenshot

![Task Tracker](assets/screenshot.png)

## Author

Colleen Cummings

Senior Technical Consultant | Cloud Engineer | Software Engineer

GitHub:
https://github.com/Geeklady55
>>>>>>> 342c40643268f8fe782edddb7803cec062cb25cc
