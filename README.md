# Rest API

## Prerequisites

- [Node.js](https://nodejs.org/): ^12.0.0
- [NPM](https://npmjs.org/) or any other Node.js package manager

### Production

To start the server use these commands:

```
nodemon src/index.js
```
To create a user, use the POST method with the following parameters:
Ex:
```
  {
    "name": "John"
  }
 ```
 
 To update a user, use the PUT method with the following parameters:
 Ex: 
 URL ```https://localhost:{port}/users/{USER ID}```
 Request Body:
 ```
    {
      "name": "Jake",
    }
 ```  
To delete a user, use the DELETE method with the following parameter in the URL:
Ex: 
 URL ```https://localhost:{port}/users/{USER ID}```
 
To view all existing users, use the GET method.
 Ex:
 URL ```https://localhost:{port}/users```
