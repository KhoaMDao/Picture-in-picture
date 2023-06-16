# Picture-in-picture

# Overview
This application is a simple, yet powerful demonstration of the Picture in Picture Web API and Screen Capture API. It provides users the ability to view any screen of their choice in a resizable Picture-in-Picture (PiP) window. The application has been developed using HTML, CSS, and JavaScript.

<img width="1467" alt="Screenshot 2023-06-16 at 9 53 32 AM" src="https://github.com/KhoaMDao/Picture-in-picture/assets/114627954/4f538eaa-d4d6-4d78-ba18-50fd484c9e01">

# Key Features and API Usage
Picture-in-Picture Web API:
The main functionality of this application is based on the Picture-in-Picture Web API. This feature is enabled when the 'START' button is clicked. The video element is then set to use the PiP mode by calling the 'requestPictureInPicture()' method on the video element.

Screen Capture API:
In conjunction with the Picture-in-Picture API, this application uses the Screen Capture API to let users select a media stream for display. The function 'navigator.mediaDevices.getDisplayMedia()' is used to prompt the user to select a screen or window to capture.

# Async/Await
Async/Await is extensively used for handling promises. It allows the application to wait for a promise to resolve or reject, making asynchronous code look and behave like synchronous code.

# Structure
The application consists of three primary files:
1. index.html: Contains the main HTML structure of the app, including the video element for the media stream and a button to initiate the PiP mode.
2. style.css: Includes the CSS rules for the application's layout and aesthetics.
3. script.js: Implements the application's functionality. It employs event listeners and asynchronous functions to manage media streams and handle the Picture-in-Picture feature.

# Setup
To use the project on your local machine, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the folder containing the project files.
3. Open the index.html file in your browser.

# Usage
After opening the index.html in a browser, you will be prompted to choose a window or screen for display in the PiP window. Once the screen is selected, go back to the PiP web and click the "START" button on the screen. The chosen screen's video will play in a movable and resizable window on the screen.

# Browser Compatibility
Ensure your web browser supports the Picture-in-Picture Web API and Screen Capture API. The application has been tested and works on modern browsers like Chrome, Firefox, and Edge.
