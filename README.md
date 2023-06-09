# Text Editor PWA

This is a text editor Progressive Web Application (PWA) that allows you to create, edit, and save notes or code snippets, with or without an internet connection. The application features data persistence techniques using IndexedDB for storing and retrieving data, ensuring reliability even in offline scenarios.

## User Story

As a developer, I want to create notes or code snippets with or without an internet connection so that I can reliably retrieve them for later use.

## Acceptance Criteria

- When opening the application in an editor, you will see a client-server folder structure.
- Running `npm run start` from the root directory will start up the backend and serve the client.
- Running the text editor application from the terminal will bundle the JavaScript files using webpack.
- After running the webpack plugins, you will have a generated HTML file, service worker, and a manifest file.
- The text editor should still function in the browser without errors, even when using next-gen JavaScript.
- When opening the text editor, IndexedDB will immediately create a database storage.
- After entering content and clicking off the DOM window, the content in the text editor will be saved with IndexedDB.
- When reopening the text editor after closing it, the previously saved content will be retrieved from IndexedDB.
- Clicking on the Install button will allow you to download the web application as an icon on your desktop.
- When loading the web application, there will be a registered service worker using workbox.
- Registering a service worker will pre-cache the static assets upon loading, including subsequent pages and static assets.
- Proper build scripts for a webpack application should be implemented for deployment to Heroku.

## Getting Started

To set up and run the Text Editor PWA, follow these steps:

1. Clone the repository:
git clone (repo)


2. Install the dependencies:
npm install


3. Start the application:
npm run start


4. Open your web browser and navigate to `http://localhost:3000` to access the Text Editor.

## Technologies Used

The Text Editor PWA utilizes the following technologies:

- JavaScript
- IndexedDB
- Webpack
- Workbox
- Heroku (for deployment)

## Deployment

To deploy the Text Editor PWA to Heroku, follow the instructions provided in the [Heroku Deployment Guide](https://<heroku-deployment-guide-url>).

## Contributing

Contributions to the Text Editor PWA are welcome! If you find any issues or have suggestions for improvements, please create a new issue or submit a pull request.
