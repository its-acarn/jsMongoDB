1. create_router.js

2. Client is responsible for the .vue files i.e anything that renders to the screen and any front-end logic. Client front-end does not speak to the db. Server links receives info from client and tells database what to do.

3. server.js makes the connection to the mongo database and creates a server to render front end.

4. gamesService.js takes functions when called in the vue files and fetches the info to be passed onto the server and database.

5. It uses the gamesService methods which then talk to the server

6. It is used for telling the server what type of request to do i.e. post/put/get. The second argument has made its own request to pass onto the router.

7. Post / Get / Delete

8. We are using it to make a connection to the database and to store the games in when they are created.

9. Because the ObjectId is used to find what item in the database we want to delete/edit etc. Otherwise we can't access it.