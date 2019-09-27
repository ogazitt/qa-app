# qa-app
Question &amp; Answer app tutorial - React + Node.js

## React front-end
Created with create-react-app.  To start the dev server, cd into frontend, start with ```npm start```

Assumes running on localhost:3001

## Node back-end
cd into backend, start with ```node src```

Listens on localhost:8081

GET serves up questions on ```/```, details of specific questions on ```/:id```

POST creates new questions on ```/```, and adds an answer to a specific question on ```/answer/:id ```

## Auth
Auth is done using Auth0.  Callback URL is http://localhost:3001/callback, handled by the react app
