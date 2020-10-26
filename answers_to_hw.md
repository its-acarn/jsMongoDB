1. create_router.js

2. Client is responsible for the .vue files i.e anything that renders to the screen and any front-end logic. Client front-end does not speak to the db. Server links receives info from client and tells database what to do.

3. server.js makes the connection to the mongo database and creates a server to render front end.

4. gamesService.js takes functions when called in the vue files and fetches the info to be passed onto the server and database.

5. It uses the gamesService methods which then talk to the server

6. 