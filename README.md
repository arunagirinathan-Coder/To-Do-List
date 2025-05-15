**To-Do List Application**
A feature-rich, responsive To-Do List web application built with HTML, CSS, and JavaScript. It allows users to manage tasks with priorities, deadlines, categories, and statuses, enhanced with smooth animations and visual effects for an engaging user experience.

**Features**

>Task Management:
Create, edit, and delete tasks.
Assign priorities (High, Medium, Low), deadlines, and categories (Work, Personal, Study, Other).
Toggle task status between Pending and Completed.


>Filtering and Sorting:
Filter tasks by status, priority, category, or due date (Today, Upcoming, Overdue).
Sort tasks by priority (High to Low, Low to High) or deadline (Earliest to Latest, Latest to Earliest).
Search tasks by title or description.


>Visual Indicators:
Color-coded priorities: Red (High), Yellow (Medium), Green (Low).
Overdue tasks highlighted in yellow.
Completed tasks grayed out with strikethrough.


>Animations and Effects:
Tasks fade in and slide from the top when added.
Tasks fade out and slide left when deleted.
Smooth scaling for completed tasks.
Hover effects with scaling and shadows on tasks.
Button click animations and input focus glow.
List fades during filter/sort updates.
Loading spinner on page load.


>Persistence: Tasks are saved to browser local storage, persisting across page refreshes.
Responsive Design: Mobile-friendly layout with adaptive form and control elements.

**Prerequisites**

A modern web browser (e.g., Chrome, Firefox, Safari, Edge).
No server or dependencies required; the app runs entirely in the browser.

**Installation**

Clone or Download the Repository:
git clone https://github.com/your-username/todo-list.git

Alternatively, download the ZIP file and extract it.

Navigate to the Project Directory:
cd todo-list


**Open the Application:**

Open index.html in a web browser by double-clicking the file or using a local server (recommended for best experience).
To run with a local server:npx http-server

Then navigate to http://localhost:8080 (or the port provided).



**Usage**

>Add a Task:
Enter a task title, optional description, select priority, category, and deadline.
Click "Add Task" to create the task.


>Edit a Task:
Click "Edit" on a task, update details in the form, and click "Update Task".


>Delete a Task:
Click "Delete" to remove a task (task slides out with animation).


>Toggle Task Status:
Check/uncheck the checkbox to mark a task as Completed or Pending (with scaling animation).


>Search Tasks:
Type in the search bar to filter tasks by title or description.


>Filter Tasks:
Use dropdowns to filter by status, priority, category, or due date.


>Sort Tasks:
Select a sorting option (priority or deadline) from the sort dropdown.


>Observe Animations:
Notice smooth transitions for adding, deleting, completing tasks, and updating filters.
Hover over tasks for scaling and shadow effects.
See input glow on focus and button scaling on click.



**Project Structure**
todo-list/
├── index.html    # Main HTML file containing structure, styles, and scripts
└── README.md     # Project documentation


The application is a single index.html file with embedded CSS (in <style>) and JavaScript (in <script>).
No external dependencies or build tools are required.

**Technologies Used**

>HTML5: For the structure of the application.
>CSS3: For styling, responsive design, and animations (keyframes, transitions).
>JavaScript: For task management logic, local storage, and animation triggers.
>Local Storage: For persisting tasks across sessions.

Screenshots
To be added: Include screenshots of the app showing the task list, form, filters, and animations.
Future Enhancements

Add notifications or reminders for tasks nearing deadlines.
Implement drag-and-drop to reorder tasks.
Add a progress bar for task completion based on deadlines.
Support task notes or attachments.
Export/import tasks as JSON.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a new branch (git checkout -b feature/your-feature).
Make your changes and commit (git commit -m "Add your feature").
Push to the branch (git push origin feature/your-feature).
Open a Pull Request.


Inspired by common task management tools and modern web design practices.
Built as a demonstration of HTML, CSS, and JavaScript capabilities with animations.


Last Updated: May 15, 2025
