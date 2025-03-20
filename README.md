# Project Name: Sandbox - Simplified Project Management

## Project Description

This project is a web application built with Python, utilizing FastAPI for the backend and Reflex for the frontend. It is managed with `uv` for Python package management. This application focuses on providing a simplified project management tool tailored for small teams.

## Key Features

- **Simplified Project Management:**
  - **Task Management:** Create, assign, and track tasks with details like title, description, due date, priority, and status.
  - **Project Organization:** Organize tasks within projects for better management and clarity.
  - **User Roles and Permissions:** Implement user authentication and authorization with different roles (e.g., administrator, team member) to control access.
  - **Intuitive Interface:** A clean and user-friendly interface for easy navigation and efficient task management.

## Tech Stack

- Backend: Python, FastAPI
- Frontend: Python, Reflex
- Package Manager: uv
- Database: PostgreSQL

## Getting Started

### Prerequisites

- Python 3.13+
- uv

### Installation

1.  Clone the repository:

    ```bash
    git clone [https://github.com/dserodio?tab=repositories](https://github.com/dserodio?tab=repositories)
    cd sandbox
    ```

2.  Install the dependencies using uv:

    ```bash
    uv sync .
    ```

3.  Set up the database:

    - Crea una base de datos con el nombre que desees.
    - Configura las variables de entorno para la conexión a la base de datos (por ejemplo, en un archivo `.env`):

    ```
    DATABASE_URL=postgresql://usuario:contraseña@servidor/basededatos
    ```

4.  Run the application:

    ```bash
    # for backend
    cd backend
    uv run uvicorn app.main:app --reload
    # for frontend (in another terminal)
    cd frontend
    uv run reflex run
    ```

## Usage

## Contributing

We welcome contributions to make this project better! Here's how you can contribute:

### Reporting Bugs

If you find a bug, please submit an issue on [GitHub Issues](https://github.com/dserodio?tab=repositories) . Include a clear description of the bug, steps to reproduce it, and any relevant error messages.

### Submitting Pull Requests

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive commit messages.
4.  Push your changes to your fork.
5.  Submit a pull request to the main branch of the original repository.

Please ensure your code follows the project's coding style and includes appropriate tests.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/).

## Contact

For any questions or suggestions, please visit my website: [www.ronnyascencio.com](www.ronnyascencio.com)
