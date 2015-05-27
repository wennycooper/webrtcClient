# webrtcClient
This is a webrtc + websocket video call example on Android.  
The client can work as a callee and a caller.

Call signaling is using my public websocket server on 

     ws://http://ec2-54-149-233-189.us-west-2.compute.amazonaws.com/:1337

You can immediately try it using chrome browser with following url:

     http://http://ec2-54-149-233-189.us-west-2.compute.amazonaws.com//wsClient.html

and then, open this app, and tap the call button  

The websocket server is not guaranteed to be always on.

## NOTE
Due to some on going commericial discussion, I just remove the source code from repo.
If you are interested to use this code, plz contact kevin.kuei.0321@gmail.com

## Demo
The following video is a robot that use the webrtc client app on Android phone and control in web app.  
https://www.youtube.com/watch?v=oUA1jU1VvC0



## Features

* Video + audio + data call establishment between Android app and Android app or between Android app and Web app
* NAT & Firewal traversal based on STUN/TURN/ICE


## How to Use
### Import websocket library (autobahn) from
    https://github.com/tavendo/AutobahnAndroid.git

### Clone this project
    git clone https://github.com/wennycooper/webrtcClient.git

### Build and run
* Add JAR into this project
* Build and run

## Known bugs
* [FIXED on 2015/04/09] Microphone not work on my Butterfly S phone. (It worked on Acer E600 phone) 

## TODOs

## References
1. https://github.com/tavendo/AutobahnAndroid
2. http://www.webrtc.org/native-code/android
3. http://html5videoguide.net/presentations/WebDirCode2012/websocket/websocket-server.js
4. http://www.html5rocks.com/en/tutorials/webrtc/basics/
5. http://www.html5rocks.com/en/tutorials/webrtc/infrastructure/#beyond-browsers-voip-telephones-and-messaging
6. http://www.gtwang.org/2014/09/webrtc-media-stream.html
