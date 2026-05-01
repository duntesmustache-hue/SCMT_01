# Social Media Data Tracker

## Project Overview
The Social Media Data Tracker is a project designed to help users analyze social media data efficiently. This document provides complete setup instructions, including backend and frontend setups and guidance on running both servers.

## Requirements
- Node.js (v14 or later)
- MongoDB (for backend)
- React (for frontend)

## Backend Setup
1. **Clone the Repository**
   ```bash
   git clone https://github.com/duntesmustache-hue/SCMT_01.git
   cd SCMT_01
   ```

2. **Install Dependencies**
   Navigate to the backend directory and install the required packages:
   ```bash
   cd backend
   npm install
   ```

3. **Setup Environment Variables**
   Create a `.env` file in the backend directory and add the following variables:
   ```plaintext
   DB_CONNECTION=<your_mongodb_connection_string>
   PORT=5000
   ```

4. **Run the Backend Server**
   ```bash
   npm start
   ```
   The backend server should now be running on `http://localhost:5000`.

## Frontend Setup
1. **Navigate to Frontend Directory**
   ```bash
   cd ../frontend
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Run the Frontend Server**
   ```bash
   npm start
   ```
   The frontend server should now be running on `http://localhost:3000`.

## Running Both Servers
- Ensure that both the backend and frontend servers are running. You can access the application at `http://localhost:3000`  and it will automatically communicate with the backend running at `http://localhost:5000`.

## Conclusion
Now you are set up to use the Social Media Data Tracker. If you encounter any issues, make sure to check your environment variables and the installed versions of Node.js and MongoDB.