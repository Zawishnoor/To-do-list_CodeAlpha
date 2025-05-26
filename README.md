**To-do-list**
This is a simple and interactive To-Do List Web Application built using HTML, CSS, and JavaScript. It allows users to add, check off, and delete tasks. Tasks are saved in local storage, so they persist even after refreshing the page.

✅ Features
✏️ Add Tasks
Type a task into the input field and click the "Add" button to include it in the list.

✅ Mark as Completed
Click on a task to toggle a check icon and strike-through style, indicating completion.

❌ Delete Tasks
Click the ❌ (cross) button to remove a task from the list.

💾 Local Storage Support
Tasks are saved in the browser's local storage and automatically loaded when the page is revisited or refreshed.

🎨 Responsive & Styled UI
Clean and modern interface styled using CSS with gradient background and custom icons (unchecked/checked state).

📁 Project Structure
bash
Copy
Edit
/project-folder
│
├── index.html         # Main HTML file
├── style.css          # CSS styling for layout and design
├── script.js          # JavaScript logic for interactivity and local storage
└── /images
     ├── to-do-list.png     # Icon next to heading
     ├── unchecked.png      # Icon for uncompleted tasks
     └── check.png          # Icon for completed tasks
🧠 How It Works
User inputs a task and clicks Add.

JavaScript creates a new <li> element with a text node and a delete <span>.

Clicking the task toggles the checked class and updates the icon using ::before.

Clicking the ❌ removes the task.

All changes are saved in localStorage.

On page load, tasks are retrieved from storage and displayed.
