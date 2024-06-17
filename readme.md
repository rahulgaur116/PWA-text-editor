## PWA Text Editor
## Description
This project is a Progressive Web Application (PWA) that serves as a text editor, allowing users to create and save notes or code snippets with or without an internet connection. The application utilizes IndexedDB for data storage, ensuring that user content is reliably saved and accessible even when offline. It features a clean and intuitive user interface, making it easy to navigate and use.

## Folder Structure
When you open the PWA Integrated Text Editor App in your editor, you will see a client server folder structure that organizes the client-side and server-side components of the application.

## Features
IndexedDB Integration: Utilizes IndexedDB to create an object store for storing user data, with GET and PUT methods for retrieving and saving content.
Offline Functionality: Works seamlessly without an internet connection, allowing users to access and edit their notes or code snippets offline.
Auto-Save Feature: Automatically saves content inside the text editor when the DOM window is unfocused, ensuring that no data is lost.
Webpack Bundling: Bundled with webpack for efficient module bundling and optimized performance.
Service Worker with Workbox: Implements a service worker with Workbox to cache static assets, enabling faster loading times and offline access.
Babel Integration: Uses Babel to enable the use of async/await syntax for asynchronous operations.
Manifest.json Generation: Includes a generated manifest.json using the WebpackPwaManifest plug-in for PWA installation capabilities.

## Getting Started
To start the application, follow these steps:
Run npm run start from the root directory to start up the backend and serve the client.
When running the text editor application from your terminal, you will notice that the JavaScript files have been bundled using webpack.
The webpack plugins will generate an HTML file, service worker, and a manifest file for the application.
The application uses next-gen JavaScript, ensuring that the text editor functions in the browser without errors.
## IndexedDB Integration
When you open the text editor, IndexedDB will immediately create a database storage for storing your content.
Enter content in the text editor and click off the DOM window to save the content with IndexedDB.
Reopen the text editor after closing it to retrieve the saved content from IndexedDB.
## Installation and Deployment
Click on the Install button to download the web application as an icon on your desktop.
When loading the web application, you will have a registered service worker using Workbox, caching static assets for faster loading.
Deploy the application to Render with proper build scripts for a webpack application.
## Technologies Used
HTML5
CSS3
JavaScript
IndexedDB
Webpack
Workbox
Babel
WebpackPwaManifest
Screenshots
Application DemoManifest.jsonService Worker RegistrationIndexedDB Storage

## Credits
This project was developed as part of the Progressive Web Applications (PWA) course on edX. Special thanks to the course instructors and mentors for their guidance and support.

## Git hub
link to github repository: https://github.com/rahulgaur116/PWA-text-editor
Link to render deployment: https://pwa-text-editor-g7cs.onrender.com/


## License
No License

## Author
Rahul Sharma 