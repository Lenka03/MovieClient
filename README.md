# Movie Reviews Application - Frontend

## Introduction

The frontend of the Movie Reviews Application is built using React.js. It connects to a remote API and MongoDB database to display and manage movie data. This part of the application handles user interactions, displaying movies, and allowing users to submit reviews.

## Technologies Used

- React.js
- Bootstrap
- Axios
- Font Awesome
- React Bootstrap
- Material UI

## Setup

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/Lenka03/MovieClient.git

2. **Install Dependencies**: 
   ```bash
   npm install

3. **Run the Application**: 
   ```bash
   npm dev start
  - *Access the frontend at localhost:3000.*

## Project Structure

- **Home Component**: The landing page, displaying a carousel of movies.
- **Hero Component**: A child component of Home, responsible for displaying the movie carousel with styling and navigation features.
- **Trailer Component**: Plays movie trailers using React Player.
- **Reviews Component**: Allows users to submit and view reviews for movies.
- **Axios Configuration**: HTTP requests are handled using Axios, with configurations set in src/api/axiosConfig.js.
- **Routing**: Managed using React Router, with route mappings defined for different components.

## Features

- **Movie Carousel**: Displays a list of movies in a carousel format using Material UI.
- **Play Trailer**: Users can click a play button on each carousel item to play a movie trailer using React Player.
- **Submit Reviews**: Users can submit reviews for movies, which are saved to the MongoDB database via API requests.

## Styling

- **Bootstrap**: Used for layout and styling.
- **Custom CSS**: Additional styling applied through hero.css and other CSS files.
- **Font Awesome**: Integrated for iconography.

## Conclusion
This frontend provides a dynamic user interface for interacting with the [moviesAPI](https://github.com/Lenka03/moviesAPI) (Movie Reviews Application's backend API), showcasing the power of React.js in building responsive and interactive web applications.

