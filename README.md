# AdminDashboardV2
Upgraded Version of AdminDashboard hey i integated typescript by replacing javascrip code
# React Admin Dashboard

This is a feature-rich **React Admin Dashboard** that includes customizable themes, responsive charts, interactive tables, calendar integration, and a Kanban board.

## ✅ TypeScript Migration

The project was originally built using **JavaScript (JSX)** and has now been successfully **updated to use TypeScript (TSX)** for enhanced type safety, better developer experience, and improved code quality.

### ✔️ What Was Updated

- All component files (`.jsx`) have been converted to `.tsx`.
- Types/interfaces have been added for:
  - Chart data (BarChart, LineChart, PieChart, etc.)
  - Props for reusable components like `InputBox`, `Table`, and `Card`
- Updated logic to utilize TypeScript features like:
  - `React.FC` (Functional Component type)
  - Type-safe `useState`, `useMemo`, `useEffect`, etc.
- Minor refactors to improve clarity and maintainability

### 💻 Technologies Used

- React + Vite
- TypeScript
- Recharts
- Tailwind CSS (or your chosen styling method)
- React Router
- Calendar/Kanban libraries (e.g., `react-big-calendar`, `react-beautiful-dnd`)

## 🚀 Getting Started

```bash
git clone https://github.com/Dinkar18/AdminDashboardV2.git
cd AdminDashboardV2
npm install
npm run dev
