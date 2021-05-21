# Express.js server for a Weather Station 

In this assignment, you will build a web server for a weather station

Since we don't have access to real weather station equipment, we will create dummy (fake) data for the server

We will save this data periodically to the server filesystem using the `fs` node module

Finally, we will send this data to any client that connects to the server and requests it

## What you will be doing

This project will allow you to practise:

> Creating a simple Express.js web server with a REST API

This project assumes you've already know:

> - JavaScript functions
> - JavaScript Math methods
> - The setInterval function
> - Promise API or async / await
> - node.js file system

## Tasks

## Task 1 - Initialising package.json

We will need to use `npm` to manage the installation of the `express` package later

To do that, we must initialise our `package.json` file

- Run the command npm init -y
  
> Note: The -y flag just tells the npm command to not bug you with annoying questions!

## Task 2 - Installing the express web server

Install the dotenv package using the following command

```shell
npm i express
```

Import the `express` package into your `server.js` file

```javascript
const express = require('express');
```

## Task 3 - Setting up a basic express.js webserver



## Task 4 - Setting up the fake data

In this part of the assignment, you will setup a function which will generate and save dummy data to a file every 60 seconds

We want the weather station to record temperature, wind speed and rainfall

For this to work, we will want to generate this information

Please choose one of the following:

- [Easy Mode](./task4/confirmEasy.md)
- [Intermediate Mode](./task4/intermediate.md)
- [Hard Mode](./task4/hard.md)

- import the node filesystem
- use setInterval to write dummy data to a file every 60 seconds
- read the file to check your function works

## Task 5 - Setting up a GET route to read the data and send it back to the client

- use the node filesystem module to read the data from the saved file
- return it to the client
