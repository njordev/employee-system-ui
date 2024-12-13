# Employee Management System: Frontend with React, Vite, and Tailwind CSS

This repository contains the frontend of the Employee Management System application, developed using React, Vite, and Tailwind CSS. It offers a user-friendly and responsive interface for managing employee data and is designed to seamlessly integrate with a separate backend.

## Features of the Frontend

### 1. **Complete Functionality:**
- User interface for creating, editing, viewing, and deleting employees.
- Responsive design for both desktop and mobile devices.
- Smooth integration with the backend through REST APIs.

### 2. **Technologies:**
- **Frontend:** React with Vite for a fast development environment.
- **Design:** Tailwind CSS for modern and customizable styling.
- **Data Communication:** Axios for API requests.

---

## Frontend Development with React, Vite, and Tailwind CSS

### a. **Project Setup**
- Create the project using Vite:
  ```bash
  npm create vite@latest employee-management-frontend --template react
  ```
- Integrate Tailwind CSS:
  - Install Tailwind CSS and its peer dependencies:
    ```bash
    npm install -D tailwindcss postcss autoprefixer
    npx tailwindcss init
    ```
  - Configure `tailwind.config.js` and `index.css` as per the [official documentation](https://tailwindcss.com/docs/installation).

### b. **Component-Based Architecture**
- **Navbar Component:** Navigation element for page control.
- **AddEmployee Component:** Form for adding new employees with validated input.
- **EmployeeList Component:** Displays all employees in a clear and structured table.

### c. **State Management and API Calls**
- **State Management:** Using `useState` and `useEffect` for dynamic data handling.
- **API Calls:** Axios for backend communication. A centralized service class manages all API interactions.

### d. **Routing and Navigation**
- Integration of React Router for navigating between different pages:
  - Employee List
  - Add Employee
  - Edit Employee

### e. **Optimizations**
- Reusable components for consistency and efficiency.
- Responsive design for various screen sizes.

---

## Setup and Installation

### Prerequisites:
- Node.js and npm
- Vite for the development environment

### Steps:
1. **Clone the Repository:**
   ```bash
   git clone
   ```
2. **Install Dependencies:**
   ```bash
   npm install
   ```
3. **Start the Development Server:**
   ```bash
   npm run dev
   ```
4. **Open the Frontend in the Browser:**
   - The development server is available by default at `http://localhost:5173`.