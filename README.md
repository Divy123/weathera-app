# Terminal Based Weather App 

This is a simple terminal based node js weather app. 
One can enter the location in terms of city and coordinates and get the weather.

## Setup

For setting up the project and downloading the dependencies, run

#### npm install 

After this, one can visit 

https://developers.google.com/maps/documentation/javascript/get-api-key

to get the user's API key which has to be replaced at Line #8 of weather.js and location.js files.

## Usage

Open your terminal and then run

```js

node app.js -l 'address'

```

or 

```js

node app.js --location 'address'

```

The results will be of the form:

temperature: 