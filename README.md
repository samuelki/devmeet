# DevMeet

> Social networking web application for developers that includes authentication, profiles, and forum posts/comments.

This web application was built using the MERN stack (MongoDB, Express, React, Node).

## Quick Start 🚀

### Add a default.json file in config folder with the following

```json
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run Express from root

```bash
npm run server
```

### Run React from /client in another terminal
```bash
cd client
npm run start
```

Check in browser on [http://localhost:5000/](http://localhost:5000/)
