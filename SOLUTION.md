Problem:
Postman can't get any data from the api

Where:
Found the problem in index.js in the app.get api request

Fix:
added '/api' in front of the data
`app.get('/api/data',`