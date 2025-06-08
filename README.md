# Task 7: Fetch and Display Data from a Public API Using Fetch API

##  Objective
The goal of this task was to fetch user data from a public API and display it on a webpage using JavaScript's Fetch API.

##  Tools Used
- **Visual Studio Code** (for development)
- **Google Chrome** (for testing)
- **HTML, CSS, JavaScript** (for implementation)
- **Public API:** https://jsonplaceholder.typicode.com/users

##  Files Included
- `index.html` – Basic webpage structure and container for data display.
- `style.css` – Styling for layout and user cards.
- `script.js` – JavaScript file that fetches data from the API and displays it dynamically.
- `screenshot.png` – Screenshot showing the webpage output. *(if available)*
- `README.md` – This file, describing the task, approach, and files.

##  What I Did
1. Created an HTML page with a container for user information and a reload button.
2. Used the Fetch API to get data from the JSONPlaceholder users endpoint.
3. Parsed the JSON response and dynamically displayed:
   - Name
   - Email
   - Address (street and city)
4. Implemented basic error handling using `.catch()`.
5. Styled the data cards using CSS.
6. Added a "Reload" button to re-fetch and refresh the displayed user data.
7. Verified functionality with and without internet connection to test error handling.
