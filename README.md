# JavaScript Authentication Page with Firebase

## Overview

This project showcases a simple login page built using JavaScript for user authentication and Firebase for backend services.

### Files Included

- `index.html`: Main HTML file structuring the login page and linking essential resources.
- `main.css`: Stylesheet containing design elements for the login page.
- `script.js`: JavaScript file handling Firebase integration and user authentication functionality.

## Components

### index.html

This file structures the login page and includes:
- HTML layout for sign-in and sign-up forms.
- Links to the CSS file for styling.
- Incorporates JavaScript for Firebase integration and user authentication.

### main.css

This file contains styling rules and design elements for the login page:
- Basic style resets for elements.
- Design and layout for input fields, buttons, and container structures.
- Button interaction styles (hover effects, etc.).

### script.js

This JavaScript file manages Firebase integration and user authentication. It includes:
- Firebase initialization and Firebase Auth service setup.
- Handling user actions: sign-in, sign-up, and form interactions.
- User authentication functionalities using Firebase's authentication methods.

## How to Use

### Initial Setup

1. Clone or download the project files.
2. Open `index.html` in a web browser.

### Firebase Setup

1. Go to the [Firebase Console](https://console.firebase.google.com/).
2. Create a new Firebase project.
3. Obtain the Firebase configuration object.

### Running the Application

- Fill in the required details in the sign-up form to create a new account.
- Use the provided email and password fields to log in to the application.

### Modification and Extension

- Customize HTML, CSS, and JavaScript files to suit your requirements.
- Ensure the Firebase configuration in `script.js` matches your Firebase project settings.
- Test the authentication process by signing up and logging in.

## Firebase Configuration

To use Firebase with this application:

1. Create a Firebase project in the Firebase Console.
2. Obtain the Firebase configuration details.
3. Replace the placeholder configuration in the `script.js` file with your actual Firebase project details.

```javascript
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
  appId: "YOUR_APP_ID",
  measurementId: "YOUR_MEASUREMENT_ID"
};
```

## Usage

- Sign in using your email and password.
- Create a new account by clicking the "Sign Up" button and filling in the required information.

## Author

This project was authored by [AJ_Styles](https://github.com/Aj3322).

Feel free to modify and extend this project as needed for your requirements.
