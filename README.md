# Jemi — Mindful Todo List & Productivity Dashboard

An exact replica of the Google Stitch **Serene Focus** design for **Jemi**, crafted with semantic HTML, Tailwind CSS, and Plus Jakarta Sans typography.

---

## ✨ Features

- **Exact Replica Design**: Faithful implementation of the Google Stitch aesthetic, color tokens (`primary: #5c4bbe`, `surface: #fcf8ff`, `secondary: #006c49`), typography, and tactile minimalist layout.
- **Dynamic Metrics**:
  - **Calm Milestone Indicator**: Real-time animated circular progress ring tracking percentage and pacing.
  - **Metric Summary Cards**: Total tasks, Pending tasks, and Completed tasks.
- **Interactive Task Management**:
  - **Add Task**: Type in the task title, pick quick category chips (`Study`, `Assignment`, `Personal`, `Errands`, `Wellness`), and add instantly.
  - **Toggle Completion**: Seamless checkbox toggle with strikethrough, subtle animation, and updated "Done at [time]" timestamp.
  - **Filter Tabs**: Instant filtering by `All`, `Pending`, or `Completed`.
  - **Delete Task**: Hover-revealed delete action with smooth transition.
  - **LocalStorage Persistence**: Tasks persist automatically across browser reloads.
- **Mindful Navigation**:
  - **Today View**: Main to-do dashboard.
  - **Upcoming View**: Scheduled upcoming agenda.
  - **Focus View**: Built-in 25-minute Pomodoro timer with progress ring.
  - **Settings & Notifications**: Popover and modal for quick actions and restoring sample data.

---

## 🚀 Running Locally

```bash
# Install dependencies
npm install

# Start the Vite development server
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser.

---

## 🛠 Project Structure

- `index.html`: Main application entry with semantic HTML, Tailwind CSS configuration, and state logic.
- `package.json`: Vite dev server configuration and scripts.
- `stitch_jemi_minimal_todo_dashboard 3/`: Original Google Stitch design assets (`DESIGN.md`, `code.html`, `screen.png`).
