## How I worked on this project

My goal was to build a streaming platform for video contents centered around comics.

- And I used Node.js, Express.js and MongoDB for this backend

## How to navigate this project

### Backend

- Express.js middleware: [link]
- API entry routes: [link to routes]
- Example of Database model with Mongoose:
- Application logic to retrieve data from the MongoDB database: [link]
- I tested this API's CRUD operations using Postman

## Why I built the project this way

### Frontend

- I used React as the major frontend library because its virtual DOM feature provides a smooth user experience whereby only necessary parts of each component are updated when state changes.
- I didn't use a state management library like Redux on purpose. For this app simple `useState` hook is sufficient. In fact, for now there's no complex logic that needs to be shared among many different components.
- Sass is a preprocessor for CSS that allows us to use the standard CSS syntax and allows us to structure our styles following component hierarchies.

### Backend

- I choose Node.js due to it does a great job at handling concurrent requests due to its asynchronous event-driven IO. A backend that is fast at processing requests and providing responses without blocking incoming requests was critical for this streaming service.
- I also used Express.js due to its popularity at managing middleware needed to manipulate the request and response objects during a request-response cycle. With express, I was able to build a fast RESTful API with all CRUD operations linking to the database.
- MongoDB was used because I needed some flexibility in type of data to store for each video item, as well as scalability as the system grow.

Testing is an essential part of production applications. Testing Library is the go-to library in the React community. I covered the essential features of the app with tests.

## Available Scripts

- `npm start` to run the backend api
