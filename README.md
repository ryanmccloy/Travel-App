# Travel Tracker App

-This is a project piece that was completed as part of an Ultimate React Course-

## How to View and Test the Portfolio Piece

To view and test this project locally, follow these steps:

1. **Download the Repository**:

   - Download the repository from GitHub:
     - Click the "Code" button and select "Download ZIP".

2. **Install Dependencies**:

   - Run the following command to install the necessary dependencies:
     - `npm install`

3. **Start the Mock Server**:

   - Run the JSON server to serve the `cities.json` file:
     - `npm run server`
   - This command will start a mock server on `http://localhost:8000` with a delay of 500ms to simulate a real backend.

4. **Start the Development Server**:

   - In a new terminal window, start the Vite development server:
     - `npm run dev`
   - This command will start the development server on `http://localhost:5173` (or another port if 5173 is in use).

5. **View the Application**:
   - Open your web browser and navigate to `http://localhost:5173` to view and test the application.

By following these steps, you will be able to view and test the portfolio piece locally with the mock server providing the necessary data.

# Overview

The Travel Tracker App is a React-based web application developed with Vite, designed to help users keep track of places they have visited.

Users can easily add, view, and manage their travel history, creating a personalized travel diary.

This project serves as a course piece, showcasing practical application of React and Vite in building interactive web applications.

# Features

- **useReducer Hook**: Provides complex state logic management.
- **Context API**: Enables state sharing across components.
- **Async Actions**: Handles asynchronous data fetching and state updates.
- **Error Handling**: Manages errors gracefully within the reducer.

Add Visited Places: Users can add locations they have visited along with dates and additional notes.

View Travel History: A comprehensive list or map view of all the places visited.

Edit and Delete Entries: Users can modify or remove their travel entries.
