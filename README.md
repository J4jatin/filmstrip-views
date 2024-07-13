# My Assignment_Solution

Images of my website-----



# Steps for how to Install and run the application

This application depends on `NodeJS` and `npm`.


### Terminal 1 (server)
```
cd server
```

**Install dependencies**
```
npm install
```

**Run tests**

Make sure that the server is not running for the tests to run as it starts its own server internally using `chai-http`.

```
npm test
```

**Start the server**

This command will start the server at `http://localhost:8081`
```
npm start
```

### Terminal 2 (client)
```
cd client
```

**Install dependencies**
```
npm install
```

**Run tests**
```
npm test
```

**Start the client**
```
npm start
```

This command will automatically open your browser window and start the client-side at `http://localhost:8080`


## Stack

### Server

The server is implemented using ExpressJS. 

### Client

The client-side is implemented using ReactJS with AxiosJS to request data from the server. 

The whole app is a single page application developed using only one ReactJS component.


