## How I worked on this project

My goal was to build a streaming platform for video contents centered around comics.

- And I used Node.js, Express.js and MongoDB for this backend

## How to navigate this project

### Backend

- Express.js middleware: [Click here](https://github.com/Lambertyubin/media_streaming_backend/blob/main/express.js#L32)
- API entry routes: [Click here to view media routes](https://github.com/Lambertyubin/media_streaming_backend/blob/main/routes/media.routes.js#L8)
- Example of Database model with Mongoose: [Media Schema](https://github.com/Lambertyubin/media_streaming_backend/blob/main/models/media.model.js#L3)
- Application logic to retrive video from database and create stream from the MongoDB database: [Streaming logic](https://github.com/Lambertyubin/media_streaming_backend/blob/main/controllers/media.controller.js#L67)
- I tested this API's CRUD operations using Postman

## Why I built the project this way

### Frontend

- [Link to Frontend](https://github.com/Lambertyubin/media_streaming_backend)

### Backend

- I choose Node.js due to it does a great job at handling concurrent requests due to its asynchronous event-driven IO. A backend that is fast at processing requests and providing responses without blocking incoming requests was critical for this streaming service.
- I also used Express.js due to its popularity at managing middleware needed to manipulate the request and response objects during a request-response cycle. With express, I was able to build a fast RESTful API with all CRUD operations linking to the database.
- MongoDB was used because I needed some flexibility in type of data to store for each video item, as well as scalability as the system grow.

Testing is an essential part of production applications. Testing Library is the go-to library in the React community. I covered the essential features of the app with tests.

## Available Scripts

- `npm start` to run the backend api
