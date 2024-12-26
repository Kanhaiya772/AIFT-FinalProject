# Employee Information Management System

This project is the culmination of the AIFT training program. It showcases the application of AI concepts in a practical scenario.
A web-based application to manage employee information efficiently. This project includes features for creating, viewing, updating, and deleting employee records with a responsive user interface.

---



## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The AIFT Final Project is designed for the demonstration of various technologies or technical tools. The project includes:

- An API for data processing.
- A frontend interface for user interaction.
- A DB file to store and manage data.

## Features

- Data processing and analysis.
- Machine learning model implementation.
- User-friendly frontend interface.
- API integration for seamless data flow.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Kanhaiya772/AIFT-FinalProject.git
   cd AIFT-FinalProject
   ```

2. **Install dependencies:**

   Ensure you have [Node.js](https://nodejs.org/) installed. Then, run:

   ```bash
   npm install
   ```

3. **Set up the database:**

   The project uses `data.db` as the database file. If it's not present, create it and run the necessary migrations.

4. **Start the development server:**

   ```bash
   npm run dev
   ```

   The application should now be running at `http://localhost:3000`.

## Usage

After setting up the project, you can access the frontend interface to interact with the application.

- Navigate to `http://localhost:3000` in your browser.
- Use the provided features to process data and view results.

## Technologies Used

- **Frontend:**
  - HTML
  - CSS (Tailwind CSS)
  - JavaScript
  - Vite

- **Backend:**
  - Node.js
  - Express.js

- **API Integration:**
  - Axios

## Project Structure

The project is organized as follows:

```
AIFT-FinalProject/
├── api/                   # API-related code
├── axios-use/             # Axios utility functions
├── public/                # Static assets
├── src/                   # Source code
│   ├── components/        # React components
│   ├── pages/             # Page components
│   ├── App.js             # Main application file
│   └── index.js           # Entry point
├── data.db                # Database file
├── index.html             # Main HTML file
├── package.json           # Project metadata and dependencies
├── postcss.config.js      # PostCSS configuration
├── tailwind.config.js     # Tailwind CSS configuration
├── vite.config.js         # Vite configuration
└── README.md              # Project documentation
```

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. **Fork the repository.**
2. **Create a new branch:**

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Make your changes and commit them:**

   ```bash
   git commit -m 'Add some feature'
   ```

4. **Push to the branch:**

   ```bash
   git push origin feature/YourFeatureName
   ```

5. **Submit a pull request.**
