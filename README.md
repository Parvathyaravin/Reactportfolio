# React-Portfolio

Week-20 Challenge (React)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](code_of_conduct.md)

## Table of Contents

- [Description](#description)

- [Live-URL](#live-url)

- [Technologies-Used](#technologies-used)

- [Installation](#installation)

- [Features](#features)

- [Usage-Information](#usage-information)

- [License](#license)

## Description

This portfolio application was developed and designed to showcase my web applications, resume, and skills to potential employers, clients, and interested parties. It was created using React an open sourced JavaScript library for building user interfaces, and Material-UI, a popular component library that implements Google's Material Design. React was created by Facebook developers and helps simplify the process of building interactive and dynamic user interfaces by providing a component-based structure, efficient rendering through the virtual DOM, and a declarative syntax. It operates via a one page application, but gives the user experience of multiple page functionality.

As it stands, this application is all front-end. However I will be looking to add a backend framework so that I can receive messages via my contact page. React allows for developer flexibility and seems to still be on the rise in popularity. React offers developers numerous options in choosing other back-end frameworks and middleware options as it is a library focused on the View layer only therefore allowing developers to build UI components leaving the choice of other libraries or tools for additional functionalities open ended.

Challenges faced when building this application resulted mainly from mixing CSS and Material UI styles and implementing the useState functionality on the nav-links. Although MUI did much of the heavy lifting, tweaking already conceived styles and adding event listener functionality turned out to be more difficult than expected as the documentation and trouble shooting are not quite as readily available as a library such as Bootstrap. In addition, adding the error handling and authentication of the contact page turned out to be rather tricky as well.

## Technologies Used

This application is powered by React.js (v18.2.0). Material UI (v5.13.6) and CSS were utilized to create the overall styling of the user interface.

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white)

## Features

Features of the site include Reacts ability to easily create a one page application that appears as though it is many pages. Users can easily navigate the site and view corresponding project code and websites from the portfolio page, download my most up to date resume as a PDF, and leave a mock message where error and authentication are required. Adding the backend framework and submit functionality are still a work in progress.

## Suggested Future Development

- Dark Mode Toggle
- Continued display and UI development
- Hamburger menu implemented on the navbar
- Potential to add additional pages for showcasing photos, travel blog, and book list
- Add backend and middleware so users can contact me (Express/MySQL, or GraphQL/MongoDB)
- Add addition of useEffect
- Including unit testing

## Contribution Guidelines

Open to collaboration, if you choose to do so open an issue and modify any changes you would like to see on a feature branch and wait for approval before merging to the main branch.

NOTICE: Contributor Covenant is released under the Creative Commons Attribution 4.0 International Public License, which requires that attribution be included.

## Test Instructions

There is currently no unit testing written yet for this application.

## License

NOTICE: This application is covered under the MIT License

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

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

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)
