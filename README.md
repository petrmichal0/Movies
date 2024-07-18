# Movies

## Project Title and Description
Movies is a web application that allows users to search for movies, view details, and manage their watched movies list.

## Badges
![Static Badge](https://img.shields.io/badge/status-online-brightgreen)

## Quick Look
<img src="https://github.com/user-attachments/assets/478544d2-9be4-4121-af72-09f896c1cb7f" width="700" alt="Movies App Demo">

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
  </tr>
  <tr>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/2af0a439-f8aa-4890-bf83-0407d1a0d018" width="300" height="300" alt="Homepage">
    </td>
    <td style="border: 1px solid black; width: 310px; height: 310px; text-align: center;">
      <img src="https://github.com/user-attachments/assets/745a3558-32dd-400a-8c65-b5e7c01a12f4" width="300" height="300" alt="Movie Details">
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


