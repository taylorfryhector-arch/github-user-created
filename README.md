# GitHub User Account Creation Date

## Overview
This web application allows users to fetch and display the account creation date of a specified GitHub username. It uses the GitHub API to retrieve the information and displays it in a user-friendly format.

## Setup and Installation
1. Clone the repository or download the project files.
2. Open `index.html` in a web browser.

## Usage
- Enter a GitHub username in the input field.
- Optionally, append `?token=YOUR_GITHUB_TOKEN` to the URL if you want to use a personal access token for authentication.
- Click the "Fetch Creation Date" button to retrieve and display the account creation date.

## Code Structure
- **index.html**: Contains the HTML structure and form for user input.
- **JavaScript**: Embedded in `index.html`, handles form submission, API requests, and displays the result.
- **Bootstrap**: Used for styling the form and layout.

## Components and Functionality
- **Form**: The form with `id='github-user-4640'` captures the GitHub username input.
- **JavaScript**: Fetches data from the GitHub API and updates the DOM with the account creation date.
- **Error Handling**: Displays error messages if the user is not found or if there is an issue with the API request.