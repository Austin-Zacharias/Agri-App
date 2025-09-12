AGRI-App Backend

This is the backend server for the FarmerHack hackathon project, built with Node.js and Express.js. It connects to a Firestore database to manage and serve data for the front-end application.
🚀 Getting Started

Follow these steps to get the server up and running on your local machine.
Prerequisites

You will need to have the following installed on your computer:

    Node.js (LTS version recommended)

    npm (comes with Node.js)

Installation

    Clone this repository to your local machine.

    Navigate into the project directory.

    Install the required dependencies by running the following command:

    npm install

Configuration

This project uses environment variables to manage sensitive information, such as your Firebase service account key.

    Create a file named .env in the root of your project directory.

    Get your Firebase service account key from your Firebase project settings.

    Add the following line to your .env file, replacing the placeholder with your actual key (make sure the entire JSON object is on a single line):

    FIREBASE_SERVICE_ACCOUNT_KEY='{"type": "service_account", ...}'

    Optionally, you can also set the port for the server:

    PORT=3000

Running the Server

To start the server, simply run the following command from your terminal:

npm start

The server will be available at http://localhost:3000 (or the port you specified). You can test it by visiting http://localhost:3000/api/ping in your browser.
📁 Project Structure

    app.js: The main server file that defines API routes and connects to Firebase.

    package.json: Lists the project's metadata and its dependencies.

    .env: Your local file containing environment variables (ignored by Git).

    .gitignore: Specifies files and folders that should not be committed to Git.

    README.md: This file, providing project documen
