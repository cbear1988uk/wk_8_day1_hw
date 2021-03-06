# Games Hub

Games Hub is a full stack JavaScript application with an Express server and MongoDB database.

## Getting Started

These instructions will get the project up and running on your local machine for development purposes.

### Installing

Install dependencies in both the client and the server folders:

```
cd client
npm install

cd server
npm install
```

Run a mongoDB server (leave running in a terminal window):

```
mongod
```

Seed the database.  Within the server folder:

```
npm run seeds
```

Run express (leave running in a terminal window).  Within the server folder:

```
npm run server:dev
```

Run Vue development environment (leave running in a terminal window).  Within client folder:

```
npm run dev
```

### Using

The application is running on port 8080 so visit http://localhost:8080/.
