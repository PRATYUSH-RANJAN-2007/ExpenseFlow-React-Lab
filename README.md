# ExpenseFlow — Personal Expense Tracker and Budget Management System

React + Vite academic project covering Component Rendering, useState, Props and React Router.

## Features
- Admin and User login/signup (new signups receive User role).
- Local Storage persistence for users, session, expenses and budget.
- Add, edit, delete, search and category-filter expenses.
- Monthly budget and dashboard statistics.
- Reports by category.
- Dynamic expense detail route using `useParams`.
- Protected routes and role-based route guards.
- `BrowserRouter`, `Routes`, `Route`, `Navigate`, `Link`, `NavLink`.
- Custom 404 page, responsive layout and dark mode.
- Reusable components receiving props: `StatCard`, `BudgetCard`, `ExpenseTable`, `ExpenseRow`, `PageHeader`.

## Demo credentials
Admin: `admin@expenseflow.demo` / `Admin123!`
User: `student@expenseflow.demo` / `Student123!`

## Run on Windows
1. Install Node.js 20 LTS (Node 18.18+ also works).
2. Extract this ZIP.
3. Open the extracted `ExpenseFlow_React_Lab_Complete` folder in VS Code.
4. Open Terminal > New Terminal. Ensure terminal path is the folder containing `package.json`.
5. Run `npm install`.
6. Run `npm run dev`.
7. Open the Vite URL shown in terminal, normally `http://localhost:5173`.

## Check production build
Run `npm run build`, then `npm run preview`.

## Lab concept map
1. Component rendering: Dashboard, Admin, Expenses, Reports, Expense Details, reusable cards/table rows.
2. useState: auth forms, expense form, search/filter, budget and theme state.
3. Props: parent pages pass data, icons, callbacks and expense records into child components.
4. Routing: login, signup, dashboard, admin, expenses, `/expenses/:id`, reports, and 404.

## Security limitation
This is a front-end academic demo. Local Storage is not secure authentication and stores demo passwords in readable browser storage. Never use real passwords or sensitive financial data. Production authentication requires a backend, password hashing, server-side authorization and a database.

## Vercel
Import the repository into Vercel, select Vite, build command `npm run build`, output directory `dist`. `vercel.json` supports refreshes on nested routes.
