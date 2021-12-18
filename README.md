# Collab-it
**A realtime collaborative text editor built with Socket.io JavaScript library along with MongoDB, Node.js, React and Quill Editor.**

## Key Features
- Real-time text collaboration using Socket.io - Multiple users can edit a document at the same time. Changes by any client are reflected to each client through sockets.
- Toolbar for text formatting like making text bold, underline, strike, along with ordered and bulleted lists and many more formatting features.
- Saving the document in the MongoDB database that allows repeat access with the document link.

## Usage

To clone and run this application, you'll need [Git](https://git-scm.com/), [Node.js](https://nodejs.org/en/) (which comes with [npm](https://www.npmjs.com/)) and [MongoDB](https://www.mongodb.com/) installed on your computer. 
From your command line:

```
# clone the repo
$ git clone https://github.com/Muskan-Saini/collab-it.git

# Go to project directory
$ cd collab-it

# Install dependencies
$ npm install

# Go to backend directory
$ cd backend

# Install dependencies
$ npm install

# Run the server
$ nodemon server.js

# Create another terminal and Run the react app
$ npm start
```

This will get the development environment started

## Tech Stack

- [Node.js](https://nodejs.org/en/): It is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code server-side.
- [`socket.io`](https://github.com/socketio/socket.io): JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers.
- [`mongoose`](https://mongoosejs.com/): An Object Data Modeling (ODM) library for MongoDB and Node.js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB.
- [`react`](https://github.com/facebook/react): Declarative, efficient, and flexible JavaScript library for building reusable UI components. It is an open-source, component-based front end library which is responsible only for the view layer of the application.
- **Quill**: Quill is a modern rich text editor built for compatibility and extensibility
- [MongoDB](https://www.mongodb.com/): MongoDB is a source-available cross-platform document-oriented database program. Classified as a NoSQL database program, MongoDB uses JSON-like documents with optional schemas.



