# Associate-Software-Developer-Assignment

**Overview**
This is a React-based web application built with Material UI and React Router, featuring a counter, user data form, and a rich text editor. The application also integrates Google Authentication for login, along with a custom password-based sign-in for user authentication.

**Key Features:**
**Counter Component:** Buttons to increment, decrement, and reset the counter, with color changes on each action.
**User Data Form:** Collects user data (name, address, email, phone), stores it in local storage, and provides notifications for unsaved changes.
**Rich Text Editor:** Allows users to view and format their data in a rich text editor with various formatting options like bold, italic, and underline.
**Authentication:** Supports Google Sign-In and custom password verification for user login.

**Demo**
You can view the live demo of the application here:
https://luminous-cat-0a933d.netlify.app/

**Functional Requirements**

**1. Counter Component**
Provides buttons to increment, decrement, and reset the count.
The background color changes dynamically in a linear fashion with a bezier curve effect.
The reset button resets both the counter and the background color.

**2. User Data Form**
Form inputs include name, address, email, and phone.
User data is saved to local storage with a unique user ID.
A warning popup is displayed if there are unsaved changes when trying to navigate away or close the browser.

**3. Rich Text Editor**
Displays user data in a rich text editor.
Supports text formatting options like bold, italic, underline, and lists.
Data persists across page reloads.

**4. Authentication**
Google Sign-In: Users can sign in via Google using Google Auth. The application works only on localhost or the deployed link.
Verification Login: Users can also log in using a verification method with the default password being 123456.

**Installation**

**Prerequisites**
Ensure you have Node.js and npm installed on your machine.

Steps to Set Up the Project Locally
Install the required dependencies:
npm install

Start the development server:
npm start

The application will be available at (https://luminous-cat-0a933d.netlify.app/)

**Authentication Details**

**Google Sign-In:**
The application uses Google Authentication via OAuth 2.0. You can sign in using your Google account.
The Google login works only when accessed either on localhost or through the deployed application link.

**Password Verification Login:**
For the password-based sign-in method, the default password is set to 123456.
When using this method, users can manually input their credentials.

**Additional Information**
State Management: The project utilizes React hooks (useState, useEffect, useContext) to manage state and component logic.
React Router: Used for routing between different components, including the counter, user data form, and rich text editor.
Material UI: Used for styling the components and making the UI responsive and modern.

**Conclusion**
This web application provides a comprehensive set of features including authentication, data persistence, and interactive components. It leverages React and Material UI to build a responsive and smooth user experience.
