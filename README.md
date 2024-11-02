# Movie Search Application

This is a simple React application that allows users to search for movies using the OMDb API. Users can type a movie title, and the app fetches information such as the movie’s title, release year, and poster image.

## Features

- **Search Input**: Users can enter the title of a movie in a search input field.
- **Responsive Grid Layout**: Movies are displayed in a responsive grid layout, ensuring a visually appealing view on all devices.
- **Real-Time Search**: Results are fetched and displayed automatically as the user types, with a debounce to minimize API calls.
- **Search Optimization**: The app avoids making redundant API calls for the same search term consecutively.

## Requirements

1. **OMDb API Key**: Sign up on [OMDb API](https://www.omdbapi.com/) to obtain an API key and add it to the project.
2. **React**: This app is built with React and requires basic setup for React apps.
