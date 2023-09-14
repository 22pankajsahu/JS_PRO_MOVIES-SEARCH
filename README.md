# JS_PRO_MOVIES-SEARCH

# Movie Search Web Application

This is a simple web application that allows users to search for movies using the OMDB API and display the results on the page.

## Table of Contents

- [Demo](#demo)
- [Screenshots](#screenshots)
- [Features](#features)
- [How it Works](#how-it-works)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## Demo

You can try the live demo of the Movie Search application [here](https://22pankajsahu.github.io/JS_PRO_MOVIES-SEARCH/).

## Screenshots

Included relevant screenshots of the application here.

![Screenshot ms1](https://github.com/22pankajsahu/JS_PRO_MOVIES-SEARCH/assets/135128502/cbf6c0ed-81f8-4d43-845b-6e949b38c683)

## Features

- Users can enter a movie name and click the "Search" button to retrieve a list of matching movies.
- The application makes an API request to OMDB to fetch movie data.
- The retrieved movie data is displayed on the page, including the movie title, poster, and year.
- The page layout is responsive and user-friendly.

## How it Works

The Movie Search web application is built using HTML, CSS, and JavaScript. Here's an overview of how it works:

1. **HTML (index.html):**

   - The HTML file sets up the structure of the web page, including input fields and containers for displaying movie results.
   - It includes a `<script>` tag to load the JavaScript code.

2. **CSS (style tag):**

   - The CSS file provides styling for various elements on the page, making it visually appealing and user-friendly.

3. **JavaScript (script tag):**

   - JavaScript code handles user interactions and API requests.

     - It listens for the "Search" button click event and triggers the `getMovie` function.
     - The `getMovie` function retrieves movie data from the OMDB API based on user input.
     - Retrieved movie data is displayed on the page by creating and appending HTML elements for each movie.
     - Error handling is implemented to handle API request errors.

## Installation

To run the Movie Search application locally, follow these steps:

1. Clone this repository: `git clone <https://github.com/22pankajsahu/JS_PRO_MOVIES-SEARCH.git>`
2. Open the `index.html` file in your web browser.

## Usage

1. Open the Movie Search application in your web browser.
2. Enter a movie name in the input field.
3. Click the "Search" button to retrieve and display matching movie results.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix: `git checkout -b feature/your-feature-name`
3. Make your changes and commit them: `git commit -m "Add your feature"`
4. Push to your branch: `git push origin feature/your-feature-name`
5. Create a pull request to the `main` branch of the original repository.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Name: [PANKAJ SAHU](https://linkedin.com/in/22pankajsahu)
- Email: [22pankajsahu@gmail.com](mailto:22pankajsahu@gmail.com)
- GitHub: [22pankajsahu](https://github.com/22pankajsahu)
