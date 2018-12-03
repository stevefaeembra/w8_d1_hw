1. What is responsible for defining the routes of the `games` resource?
> /client/helpers/request_helper

2. What are the the responsibilities of server.js?

> To hold a copy of the Mongo collection, and to communicate with Mongo, and to register the router with Express for URLs starting with '/api/games'

3. What are the responsibilities of the `gamesRouter`?

> to convert incoming CRUD restful urls into Mongo js commands to created, recall, update and delete items.

4. What process does the the client (front-end) use to communicate with the server?

> HTTP crud RESTFUL requests

5. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs

> An object containing a list of the HTTP header values to send along with the request (e.g. Method, Accept etc.)

6. Which of the games API routes does the front-end application consume (i.e. make requests to)?

> GameFormView:game-submitted and GameView:game-delete-clicked

7. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?

> To add promises / ES6 support to the queries in server/helpers/create_router.js, so we don't need to use callbacks and can just chain the various methods together asynchronously.
