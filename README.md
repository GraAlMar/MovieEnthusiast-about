# MovieEnthusiast-about


This is a project I created at the end of the web module, the second one out of the four modules in my Full Stack Developer course at Codecool. The purpose of this project was to deepen my understanding of React and non-relational databases by creating a tool for movie and TV show lovers.

## Description

MovieEnthusiast is a web application designed to cater to the preferences of cinephiles, providing a broad range of features for searching, organizing, and rating favorite movies and TV shows.

### Features:

- **Search Page**: Utilizes React with React Router to create a search interface. Users can search for movies or TV series, selecting their preferred media type via checkboxes. Results are fetched from the IMDB API and displayed as cards with titles, release years, and thumbnails. Users can easily add their favorite titles to their collection by dragging and dropping the cards onto an "Add to Favorites" area.

- **Backend with Express.js and MongoDB**: The backend, built with Express.js, manages the user's favorite movies and TV series. Favorites are stored in a MongoDB database.

- **Favorites Page**: The Favorites page displays a paginated list of the user's favorite movies and TV series. Users can filter and sort their collection based on various criteria such as title, type, release year, or genre. Additionally, they can rate their favorites using a star-rating system.

### Technology Stack:

- **Frontend**: Developed using React with React Router for navigation.

- **Backend**: Implemented with Express.js, providing RESTful API endpoints for managing user favorites. MongoDB serves as the database for storing user data.

- **Integration with IMDB API**: Utilizes the IMDB API to fetch movie and TV series data for search functionality.

- **Pagination, Filtering, and Sorting**: Favorites page features pagination for efficient browsing of large collections. Users can filter and sort their favorites based on different attributes.

- **Rating System**: Allows users to rate their favorite movies and TV series using a star-rating component.

