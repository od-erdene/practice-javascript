### _Live_ Server

> **Note**: this is _light_ taste of Node.js for absolute beginners.

Because we are loading external **.js** files our web browser will not _allow_
us to simply open the **index.html** from the directory.

Open your terminal and run this command
to _**install** the **node modules** and **start** the **live server**_:

```sh
npm install live-server --save-dev && node_modules/.bin/live-server --port=8080
```

It will take a a minute to install,
but once that's done your `live-server` will start up.

That starts a node.js HTTP server on port 8000.

> Visit: http://localhost:8080/ in your web browser
