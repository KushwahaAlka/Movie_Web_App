# Cinema Scope: Your Movie Discovery Hub

## Description

Cinema Scope is a dynamic web application built using HTML, CSS, and JavaScript that allows users to search for movies, view details, and manage a watchlist. This project leverages the OMDb API to fetch and display movie data dynamically.

## Features

**HTML:**

-   **Semantic HTML5 structure:** Utilizing elements like `<header>`, `<nav>`, `<section>`, `<article>`, and `<footer>` for a well-organized and accessible markup.
-   **Form elements:** The search bar is implemented using `<input type="text">` and `<button>`, providing a user-friendly search experience.
-   **Dynamic content:** Movie data fetched from the API is dynamically inserted into the HTML using JavaScript, resulting in a rich and interactive user interface.

**CSS:**

-   **External stylesheet (style.css):**  Centralized styling for better organization and maintainability.
-   **Responsive grid layout:** The movie display grid adapts to different screen sizes, ensuring optimal viewing on various devices.
-   **Visual enhancements:** CSS is employed to style the movie cards, buttons, and overall layout, creating an aesthetically pleasing and engaging user experience.

**JavaScript:**

-   **API interaction:** Fetches movie data from the OMDb API using asynchronous JavaScript (Fetch API) to handle data retrieval and display seamlessly.
-   **Dynamic content updates:**  JavaScript dynamically updates the HTML content based on user interactions, such as search queries and adding movies to the watchlist.
-   **Local storage:** Persists the user's watchlist using the browser's local storage, ensuring that their saved movies are available across sessions.
-   **Event handling:**  Listens for user events like button clicks and search submissions to trigger appropriate actions and update the interface dynamically.

## Functionality

1.  **Search Movies:**
    -   Users can enter a movie title in the search bar and click "Search" or press Enter.
    -   The application queries the OMDb API and displays matching movie results in a grid format.

2.  **View Movie Details:**
    -   Each movie card includes a "Details" button.
    -   Clicking this button fetches detailed information about the selected movie from the API and displays it in a modal or dedicated details section.

3.  **Manage Watchlist:**
    -   Users can add movies to their watchlist by clicking the "Add to Watchlist" button on each movie card.
    -   The watchlist is stored locally in the browser's storage, preserving it across sessions.
    -   Users can view their watchlist and remove movies as desired.

## Installation

1.  Clone the repository.
2.  Open `index.html` in a web browser.

## Usage

1.  **Search:** Enter a movie title in the search bar and click "Search".
2.  **Details:** Click "Details" on a movie card to view more information.
3.  **Watchlist:** Add or remove movies from your watchlist using the respective buttons.

## Credits

-   OMDb API: [https://www.omdbapi.com/](https://www.omdbapi.com/)

## License

This project is open-source. 
