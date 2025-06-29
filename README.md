# 📝 Todo List Application - CustomTkinter Edition

A powerful and customizable Todo List application built with **Python**, leveraging **CustomTkinter** for modern UI, **tkcalendar** for date selection, and **PIL** for image handling. It allows users to add, edit, delete, and manage tasks with due dates and priorities in a user-friendly interface.
---

## 📦 Features

* ✅ **Add/Delete/Update Tasks** with description, due date, and priority
* 🗓️ **Date Picker** using `tkcalendar.DateEntry`
* 🔁 **Recurring Reminders** with threading and real-time tracking
* 💾 **Auto-save and Load** from JSON file
* 🔍 **Task Filtering** (e.g., Today’s Tasks, Upcoming Tasks)
* 🌙 **Dark Mode UI** using `customtkinter`
* 🖼️ **Background and Icon Support** via `PIL`
* ⚠️ **Popup Alerts and MessageBoxes**
* 📉 **Overdue Task Indicator**
* 🔄 **Dynamic Task Refresh**
---

## 🛠️ Technologies Used

| Component       | Description                               |
| --------------- | ----------------------------------------- |
| `customtkinter` | Modern UI components for Tkinter          |
| `tkcalendar`    | Date selection widget                     |
| `PIL` (Pillow)  | Image loading for logos/icons             |
| `threading`     | Background updates for real-time tracking |
| `json`          | Persistent storage of tasks               |
| `datetime`      | Due date logic                            |
| `ttk`           | Additional styling widgets                |
---

## 📂 Project Structure

```bash
todo-app/
│
├── main.py              # Main Python file with TodoApp class
├── tasks.json           # Persistent storage for tasks (created on first run)
├── assets/
│   ├── logo.png         # Logo/icon for window (optional)
│   └── background.jpg   # Optional background image
```
---

## 🚀 Getting Started

### ✅ Prerequisites

Make sure the following Python packages are installed:

```bash
pip install customtkinter tkcalendar pillow
```

### ▶️ Run the App

```bash
python main.py
```
---

## 💡 How It Works

* When the app launches, it loads all tasks from `tasks.json`.
* You can add new tasks by filling in task description, date, and priority.
* Tasks are automatically sorted and displayed.
* You can edit or delete any task.
* Threads track real-time deadlines and show reminders.
* All changes are saved immediately to `tasks.json`.
---

## 🧠 Future Enhancements (Ideas)

* 🔔 Desktop notifications for task reminders
* 📱 Mobile version with Kivy or Flutter
* ☁️ Sync with Google Calendar / Firebase
* 📊 Task analytics (pie charts of completion, categories, etc.)
* 🔒 Login/Authentication system
---

## 🖼️ Screenshots

![image alt]()
---

## 🧩 Crazy Add-on Calculations? (Optional Fun)

You can even integrate this app with a "crazy calculator" from your other project to:

* Calculate time remaining in complex formulas
* Add Pomodoro timers based on task durations
* Predict productivity with gamification
---

## 🤝 Contributions
Feel free to fork and enhance the app! Submit PRs if you have ideas for better UI/UX, data persistence, or cloud features.
---

## 🛡️ License
Feel free to use, modify, and distribute.
---
