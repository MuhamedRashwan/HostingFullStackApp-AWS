# Hosting Full Stack Application

This application was provided by udacity to be used in web development nanodegree. The udagram application is a fairly simple application that includes all the major components of a Full-Stack web application.The application will be deployed on AWS.

# Overview

### Frontend Link

- http://udagram-rashwan.s3-website-us-east-1.amazonaws.com/

### Server Link

- http://udagram-env.eba-xqwk6rmg.us-east-1.elasticbeanstalk.com/

<br>

# Project Setup

 <ul>
  <li>Clone the project</li>
  <li>Install the dependencies of API <code>npm run api:install</code></li>
  <li>Create a postgres database</li>
  <li>Add the environment variables</li>
  <li>Start the server <code>npm run api:start</code></li>
  <li>Install the dependencies of Frontend <code>npm run frontend:install</code></li>
  <li>Start the Frontend <code>npm run frontend:start</code></li>
 </ul>

<br>

## Enviromental Variables Set up
Bellow are the environmental variables that needs to be set in a `.env` file. 
```bash

PORT
POSTGRES_HOST
POSTGRES_DB
POSTGRES_PORT
POSTGRES_USERNAME
POSTGRES_PASSWORD
AWS_BUCKET
AWS_PROFILE
AWS_REGION
JWT_SECRET
URL
AWS_ACCESS_KEY_ID
AWS_SECRET_ACCESS_KEY	
```

<br>

# Documentation

- [Dependencies](https://github.com/MuhamedRashwan/HostingFullStackApp-AWS/blob/main/Documentation/Dependencies.md)

- [Infrastructure description](https://github.com/MuhamedRashwan/HostingFullStackApp-AWS/blob/main/Documentation/Infrastructure%20description.md)

- [CICD Pipeline](https://github.com/MuhamedRashwan/HostingFullStackApp-AWS/blob/main/Documentation/CircleCI%20Pipeline.md)
