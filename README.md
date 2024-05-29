# MovieLand - A Simple Movie Search App

MovieLand is a simple ReactJS application that allows users to search for movies using the OMDB API. It displays the search results as a list of movie cards, showing details like the title, year, and poster.

## Features

- **Movie Search**: Users can search for movies by entering a keyword in the search bar.
- **Dynamic Results**: The app fetches and displays movies dynamically as the user searches.
- **Default Search**: On the initial load, the app displays movies related to "Batman".

## Getting Started

Follow these instructions to set up and run the project on your local machine.

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js (v14.x or later)
- npm (v6.x or later)

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/movieland.git
    cd movieland
    ```

2. **Install the dependencies:**
    ```sh
    npm install
    ```

3. **Run the application:**
    ```sh
    npm start
    ```

    This will start the development server and open the app in your default web browser. If it doesn't, navigate to `http://localhost:3000` in your browser.

### Usage

1. **Search for Movies:**
   - Use the search bar to enter a keyword (e.g., "Avengers") and click on the search icon or press `Enter`.
   - The app will display a list of movies matching the search term.

2. **View Movie Details:**
   - The movie cards show the movie title, release year, and poster image.

### Code Overview

- `App.js`: Main component that holds the state and logic for fetching and displaying movies.
- `MovieCard.js`: Component for rendering individual movie details.
- `App.css`: Styles for the application.

### API

This project uses the [OMDB API](http://www.omdbapi.com/) to fetch movie data. You need an API key to use the OMDB API. In this project, the API key is included in the code for demonstration purposes. If you want to use your own key, replace the `apikey` value in `API_URL`.

```js
const API_URL = "http://www.omdbapi.com?apikey=YOUR_API_KEY";
