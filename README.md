## cloud-server

Node.js express server hosted on AWS EC2

GUI deployment - basic express server: [http://basicexpressserver-env.eba-ammyxjfu.us-west-2.elasticbeanstalk.com/](http://basicexpressserver-env.eba-ammyxjfu.us-west-2.elasticbeanstalk.com/)

CLI deployment - cloud-server-env: [http://cloud-server-env.eba-hgstnr83.us-west-2.elasticbeanstalk.com/](http://cloud-server-env.eba-hgstnr83.us-west-2.elasticbeanstalk.com/)

## Installation

run: `git clone git@github.com:SpencerTower/express-server-deployment.git`

`cd` into express-server-deployment

## Usage

To start server, run: `npm start`

To test server, run: `npm text`

## Routes

- GET `/message`: returns a list of Message objects
- POST `/message`: creates a message, saves the message by adding it to the list of messages, and returns the list of messages.

## Features

- Message:
  - Constains String: Text
  - Constains String: Author
  - Saves messages
  - Returns list of messages
