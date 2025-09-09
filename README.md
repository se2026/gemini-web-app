# Gemini Web App

A full-stack web application built with the assistance of Gemini. This project features a React frontend and a Node.js backend.

## Features

*   **React Frontend:** A dynamic and responsive user interface built with React.
*   **Node.js Backend:** A robust backend server powered by Node.js and Express.js.
*   **API Communication:** The frontend communicates with the backend via a RESTful API.
*   **Concurrent Development:** The frontend and backend can be run concurrently with a single command.

## Technologies Used

*   **Frontend:**
    *   React
    *   Bootstrap
*   **Backend:**
    *   Node.js
    *   Express.js
*   **Development:**
    *   `concurrently` for running multiple commands.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

*   Node.js and npm: [https://nodejs.org/](https://nodejs.org/)

### Installation

1.  Clone the repo:
    ```sh
    git clone https://github.com/se2026/gemini-web-app.git
    ```
2.  Install server dependencies:
    ```sh
    cd gemini-web-app/server
    npm install
    ```
3.  Install client dependencies:
    ```sh
    cd ../client
    npm install
    ```

### Usage

1.  Navigate to the root directory of the project (`gemini-web-app`).
2.  Run the following command to start both the frontend and backend servers:
    ```sh
    npm start
    ```
3.  Open your browser and navigate to `http://localhost:3000` to see the application.
