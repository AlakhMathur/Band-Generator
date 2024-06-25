# Band Name Generator

## Description

The Band Name Generator is a web application that creates random band names based on user input. It is built using Node.js, Express, body-parser, and EJS for templating. This application serves as a fun tool for generating unique and creative band names by combining random adjectives and nouns.

## Features

- **Interactive User Interface**: Users can generate band names by simply clicking a button.
- **Random Name Generation**: The application randomly picks an adjective and a noun from predefined lists to create a unique band name each time.
- **Dynamic Content**: Displays the current year dynamically in the footer.
- **Static Styling**: Utilizes CSS for styling the web pages.

## Technologies Used

- **Node.js**: Server-side JavaScript runtime.
- **Express**: Web framework for Node.js.
- **body-parser**: Middleware to parse incoming request bodies.
- **EJS (Embedded JavaScript)**: Templating engine for generating HTML markup with plain JavaScript.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/band-name-generator.git
    cd band-name-generator
    ```

2. **Install dependencies**:
    ```bash
    npm install
    ```

## Usage

1. **Start the server**:
    ```bash
    npm start
    ```

2. **Open your browser** and navigate to `http://localhost:3000`.

3. **Generate a Band Name**: Click the "Generate Name" button to create a random band name.

## Code Overview

- **app.js**: Main server file that sets up the Express server, handles routes, and implements the band name generation logic.
- **views/**: Contains EJS templates for rendering HTML pages.
  - `index.ejs`: Main page where the band name is displayed.
  - `header.ejs` and `footer.ejs`: Partial templates for consistent header and footer across pages.
- **public/**: Contains static assets like CSS files for styling.

## Example

Here's an example of how the application works:

1. The user visits the homepage.
2. The user clicks the "Generate Name" button.
3. A new band name, composed of a random adjective and noun, is displayed.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

