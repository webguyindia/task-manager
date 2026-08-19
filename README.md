# Task Manager Dashboard

A simple yet powerful **React + Redux + Next.js** demo project showcasing modern frontend development practices.  
This project demonstrates state management with Redux Toolkit, client/server rendering in Next.js (App Router), and clean UI components.

---

## 🚀 Features
- Add, toggle, and delete tasks
- Preloaded sample tasks (Pending, In Progress, Completed)
- State management with **Redux Toolkit**
- Unique IDs generated with **UUID**
- Responsive layout with inline + global CSS
- Next.js **App Router** integration

---

## 📂 Project Structure

src/
app/
layout.js      # Wraps app with Redux Provider
page.js        # Main dashboard page
components/
AddTaskForm.js # Form to add tasks
TaskList.js    # Renders list of tasks
TaskItem.js    # Individual task item
redux/
store.js       # Redux store setup
tasksSlice.js  # Task state + reducers
styles/
globals.css    # Global styling


---

## 🛠️ Tech Stack
- **React 18**
- **Next.js 13+ (App Router)**
- **Redux Toolkit**
- **React-Redux**
- **UUID**

---

## ⚙️ Installation & Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/webguyindia/task-manager.git
   cd task-manager

2. Install dependencies:
npm install

3. Run development server:
npm run dev

4. Open http://localhost:3000 in your browser.

