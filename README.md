# Acebook

In this project, we were tasked with working on an existing application. A significant part of the challenge was to familiarise ourselves with the codebase we inherited, and work to improve and extend it.

## Existing Features

It's already possible for a user to:
- Sign up
- Sign in
- Sign out
- View a list of posts

## Architecture

This project was built using the MERN stack.

## Structure and Approach

The initial planning diagram was as follows:
<img width="1682" alt="Screenshot 2023-01-24 at 11 36 33" src="screenShots/navigation.png">
<img width="1682" alt="Screenshot 2023-01-24 at 11 36 33" src="screenShots/pages.png">

We approached the problem by first understanding the code provided to us. We then created user stories to break down the requirements into smaller, manageable tasks. We then mapped out what each page coud look like and how you ould get from one to another , creating the diagrams above.We then discussed our MVP to kick off our first sprint. We followed an agile process throughout the project with daily standups and retros after each sprint.


## Installation and Running
To install and run the code, you will need to have node and npm installed on your machine. You will need to clone the repository. Then you will need too:
1. Start the server

  **Note the use of an environment variable for the JWT secret**

   ```
   ; cd api
   ; JWT_SECRET=SUPER_SECRET npm start
   ```
2. Start the front end

  In a new terminal session...

  ```
  ; cd frontend
  ; npm start
  ```

You should now be able to open your browser and go to `http://localhost:3000/ to begin using the application.




## Testing
The backend of this application is highly tested using the Jest framework. The frontend has some test coverage using Cypress. To run the tests you need to:
### The Backend (API)

**Note the use of an environment variable for the JWT secret**

  Start the server in test mode (so that it connects to the test DB)

  ```
  ; cd api
  ; JWT_SECRET=SUPER_SECRET npm run start:test
  ```

  Then run the tests in a new terminal session

  ```
  ; cd api
  ; JWT_SECRET=SUPER_SECRET npm run test
  ```

### The frontend (React)

**Note the use of an environment variable for the JWT secret**

  Start the server in test mode (so that it connects to the test DB)

  ```
  ; cd api
  ; JWT_SECRET=SUPER_SECRET npm run start:test
  ```

  Then start the front end in a new terminal session

  ```
  ; cd frontend
  ; JWT_SECRET=SUPER_SECRET npm start
  ```

  Then run the tests in a new terminal session

  ```
  ; cd frontend
  ; JWT_SECRET=SUPER_SECRET npm run test
  ```

## Extensions
The following extensions could improve the application:
- Letting users upload pictures or videos
- Being able to search for users by name or email to find friends to add
