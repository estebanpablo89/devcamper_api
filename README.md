# DevCamper API

> Backend API for DevCamper application, which is a bootcamp directory website

## Demo

The API is live at [https://devcamper-estebanpablo89.herokuapp.com/](https://devcamper-estebanpablo89.herokuapp.com/)

## Usage

Rename "config/config.env.env" to "config/config.env" and update the values/settings to your own

## Install Dependencies

```
npm install
```

## Run App

```
# Run in dev mode
npm run dev

# Run in prod mode
npm start
```

## Database Seeder

To seed the database with users, bootcamps, courses and reviews with data from the "\_data" folder, run

```
# Destroy all data
node seeder -d

# Import all data
node seeder -i
```


Documentation at localhost [here](https://documenter.getpostman.com/view/724536/TVmFif5m)

- Version: 1.0.0
- License: MIT
- Author: Pablo Esteban
