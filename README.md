# Online-NgSpice-Simulator
This repositry contains code for Online NgSpice Simulator

## Run using Docker

    docker-compose up --build

Open browser and go to http://localhost:3000

## How to run ?

    sudo aptitude install ngspice node.js
    npm install
    node app.js

Open browser and go to http://localhost:3000

## Environment variables

####For test server
    `export NODE_ENV="testing"`

####For development
    `export NODE_ENV="development"`

####For production server
    `export NODE_ENV="production"`


## Changes

Fixed the routes to use a common function for the path for plot output.
