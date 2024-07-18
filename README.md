# Movies

## Project Title and Description
Movies is a web application that allows users to search for movies, view details, and manage their watched movies list.

## Badges
![Static Badge](https://img.shields.io/badge/status-online-brightgreen)

## Quick Look
<img src="https://github.com/user-attachments/assets/bea5cd2f-c10d-45d6-93c4-3c73094ca54f" width="700" alt="Movies App Demo">

## Table of Content
- [Project Title and Description](#project-title-and-description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Demo (link)](#demo-link)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Third-Party Libraries](#third-party-libraries)
- [License](#license)

## Features
- Search for movies
- View movie details
- Manage watched movies list

## Installation

### Prerequisites
- Node.js (v12 or higher)
- npm (v6 or higher)

### Steps

1. Clone the repository:
    ```bash
    git clone https://github.com/petrmichal0/Movies.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Movies
    ```

3. Install dependencies:
    ```bash
    npm install
    ```

## Usage
To start the application, run the following command:
```bash
npm start
```
After starting, go to [http://localhost:3000](http://localhost:3000) in your web browser.

## Screenshots

<table>
  <tr>
    <th>Homepage</th>
    <th>Movie Details</th>
    <th>Favorites List</th>
  </tr>
  <tr>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/fbcaddc0-e91d-42be-b6ab-75d07df585f5" width="300" height="300" alt="Homepage">
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/7ca12e9a-72a8-473a-8197-32b5cb20f9b6" width="300" height="300" alt="Movie Details">
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/06d571d4-6472-43b0-b22e-6ec3ea4dd273" width="300" height="300" alt="Movie Details">
    </td>
  </tr>
</table>

## Demo (link)

Check out the live demo of the application [here](https://v1-movies.netlify.app/).

## Project Structure

```css
Movies/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── components/
│   │   ├── Box.js
│   │   ├── ErrorMessage.js
│   │   ├── Loader.js
│   │   ├── Logo.js
│   │   ├── Main.js
│   │   ├── Movie.js
│   │   ├── MovieDetails.js
│   │   ├── MovieList.js
│   │   ├── NavBar.js
│   │   ├── NumResults.js
│   │   ├── Search.js
│   │   ├── Star.js
│   │   ├── StarRating.js
│   │   ├── WatchedMovie.js
│   │   ├── WatchedMoviesList.js
│   │   └── WatchedSummary.js
│   ├── hooks/
│   │   ├── useKey.js
│   │   ├── useLocalStorageState.js
│   │   └── useMovies.js
│   ├── App.js
│   ├── features.js
│   ├── index.css
│   └── index.js
├── .gitignore
├── README.md
├── package-lock.json
└── package.json
```

## Technologies Used

[![React Badge](https://img.shields.io/badge/-React-61DBFB?style=for-the-badge&labelColor=black&logo=react&logoColor=61DBFB)](#)

## Third-Party Libraries

* React Router

## License

This project is licensed under the MIT License - see the LICENSE file for details.


