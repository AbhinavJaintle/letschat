# Let'sChat - A realtime live chat server

Let'sChat messenger is a live chatting app that is developed based on NoSQL. I have mainly used NodeJs, Redis, and Socket io. HTML, CSS, and Javascript is used for the front end, NodeJS in the backend with Express and used Socket for establishing a connection. Redis DB technology is used in the backend for saving the data.


## Description

The main purpose of this app is to provide a secure way to deliver our messages using a less popular database known as Redis DB. If the popularity of Snapchat has taught us anything, it's that the messaging apps are here to survive and there is still ample room in the market for unique and creative applications.
It is a pilot project to create a base for a bigger social media networking site which would address some of the problems in the current mainstream social media sites and deliver on some new ideas.

## Methodology
There are mainly three tools in the project – Node.js, Socket.IO and Redis DB. Node.js is used to integrate web development in the project and to execute
javascript outside of the web browser. This is a good example of how node.js works:-

![alt text](https://i.ibb.co/jwZSBTz/11111.jpg)

Socket.IO allows bi-directional communication between client and server. Bi-directional communications are enabled when a client has Socket.IO in the browser, and a server has also integrated the Socket.IO package. While data can be sent in a number of forms, JSON is the simplest. To establish the connection, and to exchange data between client and server, Socket.IO uses Engine.IO. This is a lower-level implementation used under the hood. Engine.IO is used for the server implementation and Engine.IO-client
is used for the client.

![alt text](https://i.ibb.co/9bFCJP4/22222.jpg)

Redis DB in our application is used as a database initially. But once it gets some traction I will have to use it as a cache storage and then send the messages
beyond a specific limit to another database. Although redis in itself is pretty much scalable.


## Getting Started

### Dependencies

 * "ejs": "^3.1.6",
 * "express": "^4.17.1",
 * "nodemon": "^2.0.7",
 * "redis": "^3.1.2",
 * "socket.io": "^3.1.2"

### Installing

* Download the repository files and folders
```
cd folder/to/clone-into/
git clone https://github.com/AbhinavJaintle/letschat
```

### Executing program

Run:
```
node index.js
```


## Working Site

Username Page: 

![alt text](https://i.ibb.co/gMcbJCk/Screenshot-2022-07-12-041906.jpg)

Chat-Room: 

![alt text](https://i.ibb.co/SK1Sv9V/Screenshot-2022-07-12-041944.jpg)



## References

* https://redis.io/
* https://en.wikipedia.org/wiki/Redis
* https://aws.amazon.com/redis/
* https://github.com/redis/redis
* https://www.freecodecamp.org/news/how-to-learn-redis/
* https://redis.com/community/oss-projects/
* https://dev.to/valeriavg/5-ways-to-use-redis-in-your-next-project-1j2o
