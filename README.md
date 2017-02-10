# node-es-latest
A simple and fast **ES6** environment and build system for NodeJS

## Usage
My recommendation is to use the Yoman generator that scaffolds this project for you with just a few questions. You can find more information about how to use it at [yo-es-latest](https://github.com/ImanMh/yo-es-latest). If you don't want to install Yo, You can start by downloading the latest stable release and work on it's ```src``` directory.
### [Latest Release](https://api.github.com/repos/ImanMh/node-es-latest/zipball)

## About
I made this project so that I don't have to setup every simple thing that a NodeJS project definitely needs. Things such as transpiling and inline source maps are included. I tried to keep it simple and minimalistic so I don't need to use a wrecking ball to turn this project into what I need. It can simply be a starting point for any of my NodeJS projects.

## Goals
- Supporting latest **stable** version of Javascript syntax
- Startup time in development should be very fast
- Transpiling and starting of project should be done with a single command
- Cloning and starting the project should be relatively fast and without a need to do any extra configurations

At last, All the needed work to do should be simply invoking an npm or git command or downloading a zip version of the project and then starting to write code in ES6 syntax and run it without a need for extra configurations.

## Transpiling
You can transpile the project by running:

```
npm run build
```

This will output your ```src``` directory to the ```dist```.
