# turbo-module-federation
In this project, I will test the creation of projects using a mono-repo structure and Module Federation to implement micro-frontends.

# About

In this project, I tested the implementation of Turbo for managing different applications, in this case, Frontend (Vite) and Backend (Nest.js), from a mono-repo. The implementation covered basic development execution, compilation, and deployment of the backend, compiling the frontend with @nestjs/serve-static.

## Technologies Used

- **Turbo:** For efficient monorepo management.
- **Vite:** High-performance frontend bundler.
- **NestJS:** Robust framework for the backend development.
- **Module Federation:** Enables micro-frontend architecture by sharing modules dynamically.

## Running the Project

1. **Install Dependencies:**  
    Run `npm install` at the root of the repository.

2. **Start the Backend:**  
    Navigate to the backend directory and execute:
    ```
    npm run start:dev
    ```

3. **Start the Frontend:**  
    Navigate to the frontend directory and run:
    ```
    npm run dev
    ```

4. **Access the Application:**  
    Open your browser and visit `http://localhost:3000` (frontend) or the respective port for the backend.