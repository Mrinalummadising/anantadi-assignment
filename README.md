
# Video Management Application

## Overview

This is a **Video Management Application** built using the **MERN stack** (MongoDB, Express.js, React.js, Node.js). The application allows users to **upload, view, and manage their own video collections**. All services (frontend, backend, and database) are run locally inside Docker containers, with clear documentation on how to start the application.

## Features

- **Authentication & User Access**: Users can sign up and log in to access uploaded videos.
- **Video Uploading & Storage**: Users can upload videos directly from Google Drive.
- **Metadata Management**: Uploaded videos' metadata (title, description, tags, file size, etc.) is stored in a MongoDB database.
- **Filtering & Pagination**: Users can filter videos by title, date uploaded, and tags, with pagination to navigate through their collections.
- **Responsive UI**: A React-based frontend that adapts to various screen sizes, providing a user-friendly interface for managing videos.
- **Video Player**: Users can view videos directly within the application.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB 
- **Authentication**: JWT-based authentication
- **Video Upload**: Google Drive API for video uploading
- **Containerization**: Docker, Docker Compose
- **UI Design**: Responsive UI

- **Configure Docker Compose**:
   The application is set up with Docker Compose. To run all services locally, use the following command:

   ```bash
   docker-compose up --build
   ```

   This command will build and start the containers for the frontend, backend, and MongoDB database.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify) -->
