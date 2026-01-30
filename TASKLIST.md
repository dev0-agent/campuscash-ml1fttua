# Task List

This file shows the current progress of all tasks in this project.
It is automatically updated by dev0 as tasks are completed.

---

## Phase 1

- [ ] ⏳ **Initialize TanStack Start Project**
  Scaffold a new TanStack Start application. Configure Tailwind CSS for styling. specific tasks include:
- Initialize project structure.
- Install Tailwind CSS and configure `tailwind.config.js`.
- Clean up default boilerplate code to prepare for the dashboard layout.

- [ ] ⏳ **Database Schema & ORM Setup**
  Set up SQLite and Drizzle ORM. Define the database schema for `transactions` and `categories`.
- Install `drizzle-orm`, `drizzle-kit`, and `better-sqlite3`.
- Create schema: `transactions` (id, amount, description, date, categoryId) and `categories` (id, name, color).
- Run initial migration to create the local SQLite database file.

## Phase 2

- [ ] ⏳ **Implement Server Functions for Data Access**
  Create TanStack Start Server Functions to handle CRUD operations.
- Create `getTransactions`, `addTransaction`, `deleteTransaction` functions.
- Create `getCategories` and `addCategory` functions.
- Ensure strict type safety with Zod validation for inputs.

- [ ] ⏳ **Dashboard Layout & Navigation**
  Create the main application layout shell.
- Implement a responsive sidebar or top navigation bar.
- Create the root route layout (`__root.tsx`).
- Add navigation links for 'Dashboard', 'Transactions', and 'Settings'.

- [ ] ⏳ **Transaction List Component**
  Build the UI to display the list of recent transactions.
- Use the `getTransactions` server function to fetch data via a loader.
- Render a table or list view showing date, description, category, and amount.
- Format currency and dates appropriately.

- [ ] ⏳ **Add Transaction Form**
  Create a form to log new expenses.
- Inputs: Amount, Description, Date, Category (dropdown).
- Use TanStack Form or simple React state.
- Connect submission to `addTransaction` server function.
- Implement cache invalidation/router reload after submission to update the list.

## Phase 3

- [ ] ⏳ **Category Management UI**
  Allow users to manage their spending categories.
- Create a settings view to list current categories.
- Add functionality to create new categories with a name and color.
- Ensure the Transaction Form (Task 6) pulls from this dynamic list.

- [ ] ⏳ **Spending Visualization (Charts)**
  Implement a chart to visualize spending by category.
- Install `recharts`.
- Create a server function to aggregate data (sum by category).
- Render a Pie Chart or Bar Chart on the main dashboard showing where money is going.

- [ ] ⏳ **Budget Summary Cards**
  Add summary cards to the top of the dashboard.
- Calculate 'Total Spent This Month'.
- Calculate 'Remaining Budget' (hardcoded budget limit for now, e.g., $1000).
- Display these as prominent metric cards.

## Phase 4

- [ ] ⏳ **UI Polish & Responsive Design**
  Refine the visual design and mobile experience.
- Ensure the transaction form works well on mobile screens.
- Add empty states (e.g., 'No transactions yet').
- Improve loading states/skeletons while server functions are fetching.

---

_Last updated by dev0 automation_
