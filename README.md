How to create an loacalhost API endpoind that will contain the data/db.json file?

With the help of the package called "json server" which allows us to wrap a json file
with API endpoints so we can interact with it like its a REST API..

STEPS

1. install it globally:

   > npm install -g json-server - already DONE
   > ( If you want to see a list of globally installed packages (user-installed), you can add the -g flag.)

2. Serve up our JSON:

   > json-server -p 3500 -w ./data/db.json
   > (the above creates endpoint at http://localhost:3500/careers)

   -p -> for 'port'
   -w -> for 'watch'
