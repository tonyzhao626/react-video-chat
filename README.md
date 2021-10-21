## React Video Chat

A simple video chat function app developed by React. Chheck demo app at [here](https://morning-escarpment-67980.herokuapp.com).

<img align="right" width="360" src="https://raw.githubusercontent.com/tonyzhao626/react-video-chat/master/docs/ss1.jpg"  alt =" " style="border: solid 1px #d4d4d4" />
 
### Functions
Video call to your friend without registering. 
Simply send your friend your auto-generated unique ID to make the call.  
Everytime you open a new tab, the server gives you a totally different unique ID.

### Running

```
# Running server
cd server && yarn watch

# Running webpack-dev-server
cd client && yarn watch
```

**Deployment**

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/nguymin4/react-videocall/tree/production)

### Tech Stack

Frontend
- React
- Webrtc
- SCSS
- Tools: webpack2

Backend
- NodeJS
- Express
- Socket.IO