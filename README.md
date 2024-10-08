# GratiFlow

## Author

* Justin Sortland

## Project Overview

GratiFlow is a web application, which I designed to help others cultivate gratitude by creating and managing gratitude entries. The app also features user authentication, retrieval of Firebase firestore data, and sentiment analysis, which can be tracked over time on a graph located on the Profile page.

## Project Structure

* **src/components** contains UI componenets which are used on most pages on the site, such as the navigation bar (`Navbar.js`) and the font type and size selectors (`FontSelector.js`).

* **src/firebase** contains Firebase configuration (`firebase.js`) and authentication logic (`auth.js`)

* **src/pages** contains the main pages of the application, including `Dashboard.js`, `Entries.js`, `Profile.js`, etc.

## How to Run the Project

1. Extract the provided files to your local machine.

2. Navigate to the project directory (should be in the same directory as this README, alongside the `src` and `public` folders).

```
cd path/to/extracted-folder
```

3. (optional) Install Node.js if it's not already installed on your machine, since it's needed for following steps. Follow the instructions [here](https://nodejs.org/en/download/package-manager).

4. Install the dependencies.

```
npm install
```

6. Set up Firebase.

* Create a Firebase project in the Firebase console

* Within root folder, create folder called `firebase`

* Within newly created `firebase` folder, create new JS file called `firebase.js`

* Copy Firebase configuration details provided by Firebase after creating project

* Replace Firebase configuration into newly created `firebase.js` file with pasted details

* Enable Email/Password and Google authentication in Firebase Authentication

8. In the project directory, run the application with the command below.

```
npm start
```
The command above will start the development server, and the application will be accessible at `https://localhost:3000`. If it a prompt appears, requesting that you use a different port, click yes and it will still be accessible at `https://localhost:RANDOM_PORT_NUMBER_PROVIDED`.

## Video Demonstration

You can watch a video demostration of the project [here](https://drive.google.com/file/d/18J4I0SCitecHDxj9jvsrzNDF9ocMP7zY/view?usp=drive_link).

## Additional Information

* **Dependencies**: This project uses the following dependencies:
  
  * React
 
  * Firebase
 
  * React Router DOM
 
  * Tailwind CSS
 
  * Chart.js
 
  * React Wrapper
 
  * Date-fns
 
  * React Datepicker
 
  * Sentiment

* **Contact**: If you have any questions, feel free to reach out to me at `justinsortland2025@u.northwestern.edu`.
