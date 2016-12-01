A tutorial for an inventory app using the MEAN stack.
___
Created using the [MEAN Stack Tutorial](http://www.bradoncode.com/tutorials/learn-mean-stack-tutorial/) by Bradley Braithwaite (@bbraithwaite).
___
To run the project locally, type `mongod` in a terminal window. This starts mongoDB. In a new window, type `npm start`. This starts the node project. To test if you have the necessary dependencies installed, after starting your database and npm, go to `localhost:3000` by default. A MEAN.js window should appear.

To kill the mongoDB server, type `killall mongod` in a terminal window. This can also fix errors caused by having more than one instance of mongoDB running at a time.

If `mongod` fails to run, try using `chmod +x /data/db`, it's usually due to a permissions issue.

Must be using Node version 0.12.0 to run.
___

Adding user authentication kills node at the moment.


