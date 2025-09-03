# Anecdotes App

This is a small React application built as part of the [Fullstack Open
course](https://fullstackopen.com/osa1/monimutkaisempi_tila_reactin_debuggaus#tehtavat-1-6-1-14) (Osa 1, Exercises 1.12–1.14). It demonstrates React state management and handling of user interactions.

## Features

- Displays a random programming-related anecdote when clicking Next Anecdote.

- Allows users to vote for their favorite anecdotes using the Vote button.

- Tracks votes separately for each anecdote.

- Displays the anecdote with the most votes in real time.

## Technologies Used

- React

- JavaScript (ES6+)

- Functional Components

- React Hooks (useState)

## How to Run

1. Clone the repository:
   ```bash
   git clone <https://github.com/bean-123/anekdootit>
   ```
2. Navigate into the project directory:
   ```bash
   cd anekdootit
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:

   ```bash
   npm start
   ```

5. Open the app in your browser
   Go to http://localhost:3000

## Project Structure

```
anecdotes-app/
├─ App.jsx # Main React component with the application logic
├─ index.js # Entry point rendering the app to the DOM
├─ package.json # Project metadata and dependencies
├─ node_modules/ # Installed npm packages
```

## Usage

- Click `Next Anecdote` to show a new random anecdote.

- Click `Vote` to increment the vote count of the currently displayed anecdote.

- The anecdote with the most votes is displayed in a separate section.

## Notes

- The vote counts are reset when the page is refreshed.

- Random anecdotes may repeat; this is expected behavior.

### Author

Amy

## License

This project is for educational purposes as part of the Fullstack Open course.
