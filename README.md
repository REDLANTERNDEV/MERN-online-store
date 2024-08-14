# MERN Online Store
![Project](https://github-production-user-asset-6210df.s3.amazonaws.com/87618221/357862766-0a97919a-a592-4983-b7ce-2eb33289bae3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAVCODYLSA53PQK4ZA%2F20240814%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20240814T143055Z&X-Amz-Expires=300&X-Amz-Signature=31f8445788a71c50d7b0c230092f61c449e92849b8b25fb039923e2eb9e5d77c&X-Amz-SignedHeaders=host&actor_id=87618221&key_id=0&repo_id=842502002)
This project is a full-stack web application built using the MERN stack (MongoDB, Express, React, Node.js). It provides a minimal setup to get started with a MERN-based online store.

## Project Structure

- **Backend**: 
  - Express server setup
  - MongoDB integration with Mongoose
  - RESTful API for product management

- **Frontend**:
  - React with Vite for fast development
  - Chakra UI for styling
  - Zustand for state management
  - React Router for navigation



## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/mern-online-store.git
    cd mern-online-store
    ```

2. Install backend dependencies:
    ```sh
    npm install
    ```

3. Install frontend dependencies:
    ```sh
    cd frontend
    npm install
    cd ..
    ```

4. Create a [.env]file in the root directory and add your MongoDB URI:
    ```env
    MONGO_URI=your_mongodb_uri
    Dont forget to add "products" before question mark in MongoDB URI
    PORT=5000
    ```

### Running the Application

1. Start the backend server:
    ```sh
    npm run dev
    ```

2. Start the frontend development server:
    ```sh
    cd frontend
    npm run dev
    ```

## License

This project is licensed under the MIT License.
