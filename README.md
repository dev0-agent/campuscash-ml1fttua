# CampusCash 🎓💸

> Smart budget tracking for the student lifestyle.

CampusCash is a full-stack financial dashboard designed to help students track expenses, manage categories, and visualize their monthly budget trends without the complexity of enterprise accounting tools.

## Tech Stack

- **Framework:** [TanStack Start](https://tanstack.com/start/latest) (React SSR)
- **Database:** SQLite
- **ORM:** [Drizzle ORM](https://orm.drizzle.team/)
- **Styling:** Tailwind CSS
- **Visualization:** Recharts

## Features

- 📊 **Visual Dashboard:** See exactly where your money goes with interactive charts.
- 📝 **Quick Logging:** Add transactions in seconds—perfect for on-the-go students.
- 🏷️ **Custom Categories:** Organize spending into buckets like Food, Textbooks, and Transport.
- 💰 **Budget Tracking:** Monitor your total monthly spending against your limit.
- ⚡ **Full Stack Type-Safety:** End-to-end type safety using TanStack Server Functions.

## Getting Started

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd campus-cash
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Setup Database**
   This project uses a local SQLite file. Run the migration to create it:
   ```bash
   npm run db:push
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) to view the app.

## Documentation

- [TASKLIST.md](./TASKLIST.md) - Track project progress and upcoming tasks.
- [LEARNINGS.md](./LEARNINGS.md) - Developer notes and architectural decisions.
- [.dev0/RULES.md](./.dev0/RULES.md) - Project coding standards and AI guidelines.