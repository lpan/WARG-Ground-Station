# WARG Ground Station
##### The ground station that displays data received from the [data-relay-station](https://github.com/UWARG/data-relay-station)

![Screenshot](https://raw.githubusercontent.com/UWARG/WARG-Ground-Station/master/assets/screenshots/mainscreen.PNG)


# Installation
1. Clone the repo  
2. Download [Node.js](https://nodejs.org/en/) for your OS
3. Run `npm install` to install the app dependencies (which includes NW.js)
4. Download [sat_tiles.zip](https://drive.google.com/file/d/0BwjduHozuvOiaUFzV2dZdncyZnc/view?usp=sharing) and extract the `sat_tiles` folder to the assets folder of the project
5. Run `npm start` to start the app

# Building
You have the option of building a self-contained cross-platform executable of the groundstation if you so wish. To do this, simply run `npm install` to install all of the apps dependencies, then run `npm run build`. This will use [nw-builder](https://github.com/nwjs/nw-builder) to build the executable of the app and save it in the build directory.

# Running the simulation
The Ground Station supports simulations, so the data-relay-station doesn't actually have to be run. Click on the `Window>>Simulation Mode` menu item to open the simulation window and start up the simulator.

# Licence
[ISC](https://github.com/UWARG/WARG-Ground-Station/blob/master/LICENSE)

Uses [NW.js](http://nwjs.io), [Marionette](http://marionettejs.com/), and [Leaflet](http://leafletjs.com).

Map tiles are in OSM format. They can be downloaded and exported using GMapCatcher. Leaflet is the maps library used to display the tiles.
