# Daily Schedule Web Application

_Initially created in April of 2023 as a mini-project for the UCF Full-Stack Web Development Bootcamp._

## Overview

This project is a simple web-based daily schedule application that helps users organize their tasks for the day. Users can input tasks for different hours, and the application will visually indicate whether each hour is in the past, present, or future relative to the current time. Tasks are saved locally, allowing users to revisit and update their schedule at any time.

## Features

- **Dynamic Time Display**: The application displays the current date and time, updating in real-time using the Day.js library.
- **Hourly Task Input**: Users can input tasks for each hour of the day, between 8am and 7pm.
- **Color-Coded Time Blocks**: Each hour's time block is color-coded to indicate whether it is in the past, present, or future relative to the current time.
- **Local Storage**: User-entered tasks are saved locally, allowing them to persist even after refreshing the page or closing the browser.

## Technologies Used

- HTML5: Markup language for structuring the web page.
- CSS3 (Bootstrap): Used for styling and layout of the application.
- JavaScript (jQuery): Provides interactivity and dynamic behavior.
- Day.js: Library for parsing, validating, manipulating, and formatting dates and times.
- Local Storage API: Allows data to be stored locally within the user's browser.

## Usage

To use the application:

1. Open the `index.html` file in a web browser.
2. Input your tasks for each hour of the day.
3. Click the save button next to each input field to save your tasks.
4. The application will automatically update the color of each time block based on the current time.

## Local Development

To set up the project for local development:

1. Clone the repository to your local machine.
2. Open the project directory.
3. Open the `index.html` file in a web browser to view the application.

## Future Improvements

- **User Authentication**: Implement user authentication to allow multiple users to save their schedules securely.
- **Data Syncing**: Enable synchronization of schedules across multiple devices.
- **Additional Features**: Add features such as task prioritization, recurring tasks, and reminders.

## License

This project is licensed under the [MIT License](LICENSE).
