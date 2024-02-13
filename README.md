
# Personal Reading List Application

## Description

This web application is designed to help users manage their personal reading lists. Built with Vue.js and Firebase, it features user authentication, real-time database updates, and interactive UI components. Users can sign up, log in, add books to their reading list, and view their collection in real-time.

## Technologies Used

- **Vue.js 3**: A progressive JavaScript framework used for building user interfaces. [Vue.js Documentation](https://v3.vuejs.org/)
- **Firebase**: A comprehensive app development platform by Google, used here for authentication, database, and hosting services. [Firebase Documentation](https://firebase.google.com/docs)
  - **Firestore**: For real-time database operations. [Firestore Documentation](https://firebase.google.com/docs/firestore)
  - **Firebase Authentication**: For managing user authentication. [Authentication Documentation](https://firebase.google.com/docs/auth)
- **Vue Router 4**: For client-side routing. [Vue Router Documentation](https://next.router.vuejs.org/)

## Project Setup

1. Clone the repository to your local machine.
2. Install dependencies with `npm install`.
3. Start the development server with `npm run serve`.

```bash
npm install
npm run serve
```

## Features

- **User Authentication**: Sign up, log in, and manage your account.
- **Reading List Management**: Add and remove books from your personalized reading list.
- **Real-Time Updates**: Changes to your reading list are updated in real-time across all devices.

## Project Structure

- `src/main.js`: Entry point for the Vue application.
- `src/App.vue`: The main application component.
- `src/components/`: Contains Vue components for the UI.
- `src/composables/`: Reusable composition functions, particularly for Firebase interactions.
- `src/router/index.js`: Configuration for Vue Router.
- `src/firebase/`: Firebase configuration and initial setup.

## Running the Application

Use `npm run serve` to start a local development server. Access the application at `http://localhost:8080`.

## Building for Production

To create a production build, use `npm run build`. Deploy the `dist/` folder to your preferred hosting service.
