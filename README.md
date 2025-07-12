# To-Do List App

A modern, interactive To-Do List application built with vanilla JavaScript, HTML, and CSS. This app helps you manage your daily tasks, set deadlines, and keep track of your progress with a clean and responsive interface.

---

## Features

### 📝 Add Tasks

- Quickly add new tasks with a title, optional note, and a deadline.
- Input validation ensures you can't add empty tasks or duplicate deadlines.

### ⏰ Deadlines & Countdown

- Set a specific date and time for each task.
- Each task displays a live countdown timer showing days, hours, minutes, and seconds remaining until the deadline.
- When a deadline is reached, the app notifies you with a clear message.

### ✅ Complete & Remove Tasks

- Mark tasks as complete using the checkbox.
- Completed tasks slide out and are removed from both the UI and local storage after a short animation.

### 🗃️ Persistent Storage

- All tasks are saved in your browser's **local storage**.
- Your to-do list is automatically restored every time you reload or revisit the app.

### 🗂️ Task Details Modal

- Click on any task to view its full details in a modal window.
- See the task's title, note, and a live-updating countdown.
- Easily close the modal with the close button or the Escape key.

### 🧹 Clean UI & Responsive Design

- Minimalist, distraction-free layout.
- Responsive design works well on both desktop and mobile devices.
- Smooth animations for adding, removing, and viewing tasks.

### 🔄 Real-Time Updates

- Countdown timers update every second.
- The UI updates instantly when you add, complete, or remove tasks.

### 🛡️ Data Integrity

- Prevents duplicate tasks with the same title and deadline.
- Handles invalid or missing input gracefully.

---

## Getting Started

1. **Clone or Download** this repository.
2. Open `index.html` in your browser.
3. Start adding, completing, and managing your tasks!

---

## Usage Tips

- Click the **Add** button to open the modal and create a new task.
- Fill in the task title, optional note, and select a deadline.
- Click on any task to view its details and countdown.
- Mark a task as complete by checking its box; it will be removed after a short animation.
- All your tasks are saved automatically—no need to worry about losing your list!

---

## Tech Stack

- **JavaScript** (ES6+)
- **HTML5**
- **CSS3**
