# TodoList with Node
Simple Todo list api, with a react front end.

Hello, if you would like to see this in action clone it.

Make sure you have node installed on your OS then run the command npm i inside the same directory as package.json.

Also you'll need to run a MongoDb database locally. To do so run these commands.
sudo apt-get install -y mongodb-org
echo 'mongod --bind_ip=$IP --dbpath=data --nojournal --rest "$@"' > mongod
chmod a+x mongod
./mongod        --this command starts your database inside of the terminal.

Inside of a new terminal run the Node Index.js command. This will start the server on the available port.

If you don't have sudo commands on your machine try doing these inside of a cloud 9 workspace. 

The port is set to cloud9 pvn | localhost:3000 by default. Have fun with the api and do whatever you'd like from there!
