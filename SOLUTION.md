Problem: 
`POST http://localhost:3000/api/data 500 (Internal Server Error)`
Whenever you tried to post to the api

Where:
Index.js

Fix:
Found that bodyParser was not being used with .json
`app.use(bodyParser.json());`