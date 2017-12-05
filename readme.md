# Getting started 

 First, you will need a static server to run `server.js` locally. Install `node-static` if you don't already have it. Alternatively, you could probably use another static node server, like `http-server`, but for simplicity's sake, let's just stick with `node-static`.

```sudo npm install -g node-static```

Then install the rest of the dependencies using `npm install`. 

From the root, run he command `static`. This will start up the static server and run `client.js`.

Then, `cd js` and run the command `node server`. This will start the signaling (websocket) server.

Tutorial can be found [here](https://www.tutorialspoint.com/webrtc/webrtc_text_demo.htm)
