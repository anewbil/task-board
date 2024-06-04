# task-board
Welcome to our project task board! This task board is designed to help you manage your project efficiently by organizing tasks based on their progress state and providing visual indicators for deadlines.

Features
Task Progress Visualization
When you open the task board, you'll see a list of project tasks organized into columns representing their progress state: Not Yet Started, In Progress, and Completed.
Deadline Status
Each task is color-coded to indicate its deadline status:
Yellow: Nearing the deadline
Red: Overdue
Task Creation
Click on the "Define New Task" button to create a new task.
You can enter the title, description, and deadline date for the new task into a modal dialog.
Task Persistence
After saving a task, its properties are stored in localStorage, ensuring that your tasks persist even if you refresh the page.
Task Progress Update
Dragging a task to a different progress column will update its progress state accordingly.
The updated progress state will stay in place even after refreshing the page.
Task Deletion
To delete a task, simply click on the delete button associated with that task.
Deleted tasks will be removed from the task board and won't reappear after refreshing.
Usage
Open the task board.
View and manage tasks based on their progress and deadline status.
Define new tasks using the provided modal dialog.
Update task progress by dragging tasks between progress columns.
Delete tasks as needed.
Technical Details
The task board utilizes localStorage to store task data, ensuring persistence across page refreshes.
Task progress is updated dynamically using drag-and-drop functionality.
Deadline status is visually indicated through color-coded task elements.
Dependencies
This task board may require modern web browsers with support for HTML5, CSS3, and JavaScript.
No additional dependencies are needed as the task board handles data storage locally.

Feedback
Your feedback is valuable to us! If you encounter any issues or have suggestions for improvements, please don't hesitate to reach out.