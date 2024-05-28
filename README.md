# Forum Project

Welcome to the Forum Project! This project consists of a frontend and backend to create a fully functional forum application.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Starting the Project](#starting-the-project)
  - [Starting the Backend](#starting-the-backend)
  - [Starting the Frontend](#starting-the-frontend)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have met the following requirements:
- Node.js installed on your machine
- npm (Node Package Manager) installed
- Git installed

## Installation

To set up the project locally, follow these steps:

1. **Clone the repositories:**

   ```bash
   git clone <backend-repo-url>
   git clone <frontend-repo-url>
   ```

2. **Navigate to the backend directory and install dependencies:**

   ```bash
   cd <backend-directory>
   npm install
   ```

3. **Navigate to the frontend directory and install dependencies:**

   ```bash
   cd <frontend-directory>
   npm install
   ```

## Starting the Project

### Starting the Backend

To start the backend server, navigate to the backend directory and run:

```bash
npm run start:dev
```

This command will start the backend server in development mode.

### Starting the Frontend

To start the frontend application, navigate to the frontend directory and run:

```bash
npm run start
```

This command will start the frontend server and open the application in your default web browser.

## Project Structure

Here is a brief overview of the project structure:

```
backend/
  ├── src/
  ├── package.json
  ├── tsconfig.json
  └── ...

frontend/
  ├── src/
  ├── public/
  ├── package.json
  └── ...
```

- `backend/` - Contains the backend code of the forum application.
- `frontend/` - Contains the frontend code of the forum application.

## Contributing

Contributions are always welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for using the Forum Project! If you have any questions, feel free to open an issue or contact the project maintainers.
