# Netflix Clone

A Netflix clone website built using React.js, Firebase for user authentication, and TMDB API for fetching movie data.

## Features

- **User Authentication**: Login and Sign-up functionality implemented using Firebase Authentication.
- **Home Page**: Displays categorized movie sections such as:
    - Popular on Netflix
    - Blockbuster Movies
    - Only on Netflix
    - Other categories
- **Dynamic Movie Data**: Movies and TV shows are fetched dynamically from the TMDB API.

## Tech Stack

- **Frontend**: React.js, CSS
- **Backend**: Firebase Authentication
- **API**: TMDB (The Movie Database)

## Installation

1. Clone the repository:
     ```bash
     git clone https://github.com/your-username/netflix-clone.git
     cd netflix-clone
     ```

2. Install dependencies:
     ```bash
     npm install
     ```

3. Create a `.env` file in the root directory and add the following environment variables:
     ```env
     REACT_APP_FIREBASE_API_KEY=your_firebase_api_key
     REACT_APP_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
     REACT_APP_FIREBASE_PROJECT_ID=your_firebase_project_id
     REACT_APP_TMDB_API_KEY=your_tmdb_api_key
     ```

4. Start the development server:
     ```bash
     npm start
     ```

## Usage

- Visit the login or sign-up page to create an account or log in.
- Browse through the categorized movie sections on the home page.
- Enjoy the Netflix-like experience!

## API Reference

- **TMDB API**: [https://www.themoviedb.org/documentation/api](https://www.themoviedb.org/documentation/api)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [React.js Documentation](https://reactjs.org/docs/getting-started.html)
- [Firebase Documentation](https://firebase.google.com/docs)
- [TMDB API Documentation](https://www.themoviedb.org/documentation/api)

Feel free to contribute to this project by submitting issues or pull requests!