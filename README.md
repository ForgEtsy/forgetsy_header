# forgEtsy header & search bar

Link to microservice demo - https://bit.ly/2oqtf5r


### Technologies
Frontend: TypeScript, React, React Router & CSS Modules

Backend: Node, Express, MongoDB & Mongoose

Deployment: Docker, Docker-compose, AWS EC2

![header demo](https://thumbs.gfycat.com/CavernousAdmiredCod-size_restricted.gif)

### Entry

App.tsx is the entry point for any changes to react router/initial router changes. Otherwise, actual component logic starts in `AboveMainContent`

### Scripts

`npm run start:dev` for local development will, check the linter and if it passes start the application

`npm run server:dev` to build the application, and run it in node.

### Deployment

`docker-compose up` will containerize the applictaion, and spin up the db
make sure `database/db.js` has the host set to `mongo` and not `localhost`, or else you will not be able to access the db.
