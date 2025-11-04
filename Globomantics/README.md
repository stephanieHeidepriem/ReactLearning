# ReactLearning
Repo for React Learning Courses on Pluralsight

# Planned Courses: React Fundamentals & Authorication and Authorization

15.10.2025: Foundamentals Module 3
01.11.2025: Foundamentals Module 4 (Styling Components) --> (16.10.2025)
02.11.2025: Foundamentals Module 5 (Hooks, Props and Stat) --> (17.10.2025)
02.11.2025: Foundamentals Module 6 (Component Rendering and Side Effects) --> (18.10.2025)
02.11.2025: Foundamentals Module 7 (Conditional Rendering and Shared State) --> (19.10.2025)
03.11.2025: Foundamentals Module 8 (Context and Navigation) --> (20.10.2025)
04.11.2025: Foundamentals Module 9 (User Input and Forms) --> (21.10.2025)
04.11.2025: Foundamentals Module 10 (Server-side React and Next.js) --> (22.10.2025)
04.11.2025: Foundamentals Module 11 (Application Design) --> (23.10.2025)


# Aufsetzen des Environments
- install nodejs: https://nodejs.org/en/download
- npm install
- Install ESLint Extension



Repository mit fertigem Code: https://github.com/RolandGuijt/react-fundamentals
- npm install
- npm run dev
Repository mit fertigem Code Authentication and Authorization: https://github.com/RolandGuijt/ps-reactauth


# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

#Befehle
- npm run lint 

## Zu beachten!
- prop die an eine Komponente weitergegeben werden sind Readonly! Komponenten sollten niemals ihre eigenen Übergabeparameter ändern, weil das in die Hose geht mit den referenzierten Komponenten und Fehler verursacht, die sich durchziehen und schwer zu finden sind.

When tu Use React.memo
- when it's faster
- Mesure
- Pure functional component
- Renders often with the same prop values
- jsx should be easy