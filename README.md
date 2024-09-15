TO DO LIST 
A simple to-do list application implemented in a Jupyter Notebook using Python. This notebook allows you to manage your tasks interactively within the notebook interface.

FEATURES
1. Add a new task: Input and save tasks to a list.
2. View all tasks: Display all tasks currently saved.
3. Remove a task: Delete a specific task by its number.
4. Persistency: Tasks are stored in a file named tasks.txt in the current directory

HOW TO USE
1. Open the Notebook: Launch Jupyter Notebook and open the to-do-list.ipynb file.
2. Run the Cells: Execute the cell that initializes the required functions and variables. This cell sets up the environment and prepares the notebook for interaction.
3. Interact with the To-Do List:
Add a New Task: Run the cell that calls the add_task() function. Follow the prompt to enter the task description.
View All Tasks: Run the cell that calls the view_tasks() function to see the list of current tasks.
Remove a Task: Run the cell that calls the remove_task() function. You will be prompted to enter the number of the task you want to remove
4. Exit: To stop using the to-do list, simply stop running the cells.

NOTES
1. Tasks are saved in tasks.txt in the same directory as the notebook. Ensure the notebook has write permissions to this directory.
2. Tasks are stored persistently in the file across sessions, but the notebook itself does not provide a graphical user interface (GUI); it runs in the text-based Jupyter Notebook interface.

