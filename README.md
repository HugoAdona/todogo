# TodoGo

## Overview

This repository contains the source code for TodoGo, a minimalist to-do list web application designed to help users efficiently organize their daily tasks. The app features a clean, mobile-inspired interface with task creation, editing, deletion, and local storage persistence.

## Features

- **Task Management**: Add, edit, and delete tasks with title, due date, and description fields.
- **Local Storage**: Tasks are saved in the browser's local storage for persistence across sessions.
- **Responsive Design**: Optimized for a mobile-like experience with a fixed-size app container.
- **Interactive UI**: Includes hover and click animations for buttons and task options.
- **Modal Form**: A Bootstrap modal for adding and editing tasks with form validation.
- **Tailwind CSS Styling**: Modern, utility-first CSS for a cohesive and polished look.

## Technologies Used

- **HTML5**: Semantic structure for the app's interface (`index.html`).
- **CSS3**: Tailwind CSS (`output.css`) compiled from `input.css` for styling.
- **JavaScript**: Handles task CRUD operations, form validation, and local storage in `script.js`.
- **Bootstrap 5**: Provides the modal component for task input.
- **Font Awesome**: Icons for task edit, delete, and add actions.

## File Structure

- `index.html`: Main HTML file containing the app structure and task form modal.
- `styles.css`: Main CSS file with custom styles.
- `script.js`: JavaScript for task management, form handling, and local storage.
- `assets/`: Directory for static resources (e.g., icons, if any).

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/HugoAdona/todogo.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd todogo
   ```
3. **Open the Website**:
   - Open `index.html` in a web browser to view the app locally.
   - Alternatively, serve the project using a local server (e.g., `live-server` or Python's `http.server`):
     ```bash
     python -m http.server 8000
     ```
     Then visit `http://localhost:8000` in your browser.

## Usage

- **Add a Task**: Click the "Add New Task" button to open the modal, fill in the task title (required), due date, and description, then click "Add".
- **Edit a Task**: Click the edit icon (`fa-edit`) on a task to populate the modal with its details, update the fields, and save.
- **Delete a Task**: Click the delete icon (`fa-trash-alt`) to remove a task.
- **View Tasks**: Tasks are displayed in a grid with title, date, description, and action icons.
- **Persistence**: Tasks are automatically saved to local storage and persist across browser sessions.

## Deployment

The website is deployed on GitHub Pages at [https://hugoadona.github.io/todogo](https://hugoadona.github.io/todogo). To deploy updates:

1. Push changes to the `main` branch.
2. Ensure GitHub Pages is configured to serve from the `main` branch in the repository settings.

## Contributing

This is a personal project, but feedback and suggestions are welcome! Feel free to open an issue or submit a pull request with improvements.

## License

© 2025 Hugo Adona. All rights reserved.

## Contact

Connect with me via:

- [GitHub](https://github.com/HugoAdona)
- [Instagram](https://www.instagram.com/hugoadona)
- [X](https://x.com/hugoadona)