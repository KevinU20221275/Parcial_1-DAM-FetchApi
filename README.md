# Movie Search App

A simple web application to search for movies using the [OMDb API](http://www.omdbapi.com/).

## Features
- Search movies by title.
- Display movie poster, title, year, and description.
- Handles errors and missing posters gracefully.
- Simple and responsive layout with basic animations.

## Installation
1. Clone the repository:
```bash
git clone https://github.com/KevinU20221275/Parcial_1-DAM-FetchApi.git
```

2. Open **index.html** in your browser.

## Folder structure

```text
|-/assets
|    |- /css -> stylesheets
|    |- /js  -> JavaScript code
|    |- /img -> default images used by the app
|    |- /mocks -> mock API responses for testing
|
|- index.html
|
|-/docs
     |- /screenshots -> images for README and documentation
```

App Screenshots:

### Default load
App opens with the initial movie displayed.

![Default Movie](docs/screenshots/default.png)

### Movie Found
Successful search showing movie details.

![Movie Found](docs/screenshots/success.png)

### Movie Not Found
Shows placeholder when no results are found.

![Not Found](docs/screenshots/not-found.png)

### Error
Displayed when the API request fails.

![Error](docs/screenshots/error.png)

## Notes
- The app initializes with "Inception" as the default movie.
- Press Enter in the search input to trigger a new movie search.
- Movies without posters show a default image (defaultBg.png).
- Errors or failed API requests show an error image (badMovieRes.png).