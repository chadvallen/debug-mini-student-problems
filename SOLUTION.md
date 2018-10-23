Problem: 
api request was not displaying any data that was given

Where:
fetchData() function inside of MyComponent.js

Fix:
`this.setState({ data: response.data.results });`
I console.log() until i found out we needed to go into each index in the api array to find name