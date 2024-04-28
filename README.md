# Project Management Application

The Project Management App is a user-friendly web-based tool crafted to streamline project management processes and enhance team collaboration. Offering functionalities such as project creation, to-do list management, it delivers a holistic solution for efficiently managing projects.
## Features

- *Project Management*:
  - Create new projects with title, and creation date, subtask.
  - List all projects on the home page for easy access.
  - View detailed project information including title and list of todos.
- *Todo Management*:
  - Introduce new tasks to a project with distinctive identifiers, descriptions, statuses, creation dates, and last updated dates.
  - Modify existing tasks to reflect changes in their status.
  - Flag tasks as completed or pending.
- *Export Summary as Gist*:
  - Generate project summary in markdown format.
  - Export the summary as a secret gist on GitHub with the following format:
    - File name: <Project title>.md
    - Project title as heading.
    - Summary: <No. of completed todos> / <No. of total todos> completed.
    
## Technologies Used
- Backend: Python Flask
- Frontend: HTML, CSS, JS
- Database: MongoDB
