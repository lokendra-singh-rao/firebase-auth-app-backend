# Simple React JS Project

## What is the use of this Repo

This Project is a Simple ReactJS Project which demonstrates the following
1. Creating a Component in React
2. Making HTTP calls
3. Communicating between parent and child component
4. Using Bootstrap along with React
5. Using Basic Routing in React

The project Template can be used to build bigger projects

## Live Application URL

### https://aditya-sridhar.github.io/simple-reactjs-app
This URL has the application deployed in

## Prerequisites

### Install Node JS
Refer to https://nodejs.org/en/ to install nodejs

### Install create-react-app
Install create-react-app npm package globally. This will help to easily run the project and also build the source files easily. Use the following command to install create-react-app

```bash
npm install -g create-react-app
```
## Live Application URL

The Application is deployed in https://aditya-sridhar.github.io/simple-reactjs-app

Click on the link to see the application

## Cloning and Running the Application in local

Clone the project into local

Install all the npm packages. Go into the project folder and type the following command to install all npm packages

```bash
npm install
```

In order to run the application Type the following command

```bash
npm start
```

The Application Runs on **localhost:3000**

## Application design

#### Components

1. **Customers** Component : This Component displays a list of customers. This Component gets the data from a json file in assets folder

2. **CustomerDetails** Component : This Component Displays the details of the selected customer. This Component gets its data from a json file in assets folder as well. This Component is the Child Component of *Customers* Component

#### HTTP client

**axios** library is used to make HTTP Calls

#### URL

The application has just one url /customerlist which ties to *Customers* Component

## Resources

**create-react-app** : The following link has all the commands that can be used with create-react-app
https://github.com/facebook/create-react-app

**ReactJS** : Refer to https://reactjs.org/ to understand the concepts of ReactJS

**React Bootstrap** : Refer to https://react-bootstrap.github.io/getting-started/introduction/ to understand how to use React Bootstrap




# Firebase Authentication Backend
This is the backend Java application for a Firebase authentication app. It provides GraphQL APIs for user authentication using Firebase Authentication. The application is built with Spring Boot and communicates with Firebase to manage user authentication and MongoDB to manage user data.

## Features
User Authentication: Implement sign-up, and sign-in functionalities.
Database Interaction: Save and retrieve user's authentication data from Firebase Firestore and user's personal data to/from MongoDB. 

## Technologies Used
Java
Spring Boot
Firebase Authentication
Firebase Firestore
MongoDB 

## Getting Started
To run the application locally, follow these steps:

### Clone this repository.
Set up your Firebase project and add the necessary credentials to the application in FirebaseCofig.java file.
Set up your MongoDB account and add the necessary credentials to the application.properties file.

### Build and run the application using Gradle on your preferred IDE (I used STS-4.21.1).
Build using terminal using command
```bash
./gradlew build
```
Run using
```bash
./gradlew bootRun
```
OR
Run as Spring Boot App using default configurations of IDEs 


## Usage
Ensure the backend is running.
Use the frontend application (https://github.com/lokendra-singh-rao/firebase-auth-app-frontend) to interact with the authentication APIs.

## Contributors
### Lokendra Singh Rao (https://github.com/lokendra-singh-rao/)


Feel free to customize this repo with more specific details about your project, such as installation instructions, API documentation, or additional features.
