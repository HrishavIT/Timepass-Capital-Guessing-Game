# Capital Guessing Game

An interactive web-based quiz where players test their knowledge of world capitals by guessing the capital city of a randomly selected country.

## Features

- Randomly selects a country from the database
- Allows users to guess the corresponding capital
- Case-insensitive answer checking
- Keeps track of the player's score
- Displays a new question after every submission
- Uses PostgreSQL to store country and capital data
- Server-side rendering with EJS

## Tech Stack

- **Node.js** – Runtime environment
- **Express.js** – Web server and routing
- **PostgreSQL** – Database for storing countries and capitals
- **EJS** – Server-side templating
- **JavaScript** – Application logic
- **HTML/CSS** – Frontend
- **dotenv** – Environment variable management

## Project Structure

```text
Capital-Guessing-Game/
│
├── public/             # Static files (CSS, images, etc.)
├── views/              # EJS templates
│   └── index.ejs
│
├── index.js            # Express server and application logic
├── package.json        # Project dependencies and scripts
├── capitals.csv        # Country and capital data
├── .env.example        # Example environment variables
└── .gitignore          # Ignored files and folders
