Questions:

1) What is responsible for defining the routes of the games resource?
  * createRouter. Which is pulling from a collection of GETS, PUTS, POSTS, DELETES, etc..
  Each of which are able to be assigned to different URL's.

2) What do you notice about the folder structure? Whats the client responsible for? Whats the server responsible for?
  * Client is responsible for the front end of the app. Creating an environment form
  the user to navigate and access functionality.
  Server is holding together the database and the overall methods/functions that the
  app is capable of.

3) What are the the responsibilities of server.js?
  * Server.js is connecting the front end with the back end. Navigating what pulls from where and basically acting as a hub to direct how the app pulls from the
  database.

4) What are the responsibilities of the gamesRouter?
  * Deleting games.

5) What process does the the client (front-end) use to communicate with the server?
  * The components are connecting to the server via fetching the API.

6) What optional second argument does the fetch method take? And what is it used for in this application? Hint: See Using Fetch on the MDN docs
  * ??

7) Which of the games API routes does the front-end application consume (i.e. make requests to)?
  * GameForm. It pulls information given by the user and adds it to the API.

8) What are we using the MongoDB Driver for?
  * To store data.
