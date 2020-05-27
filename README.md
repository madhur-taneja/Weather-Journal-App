# Weather-Journal App

An asynchronous web app that uses Web API and user data to dynamically update the UI. 

## Table of Contents
- [Getting Started](#getting-started)
	- [Tools Required](#tools-required)
	- [Installation](#installation)
	- [Instructions](#instructions)
	- [Extras](#extras)
- [Development](#development)
- [Running the App](#running-the-app)
- [References](#references)

## Getting Started

The starter code can be found in [this](https://github.com/udacity/fend/tree/refresh-2019) repo provided by Udacity. 

The project will be evaluated by a Udacity code reviewer according to the project [rubric](https://review.udacity.com/#!/rubrics/2655/view).

### Tools Required
You would require the following tools to develop and run the project:

* [node.js](https://nodejs.org/en/)
* [npm](https://www.npmjs.com/)
* A text-editor of your choice. 

### Installation

Start by setting up the project environment. `cd` into the project's root folder and run the following command to install the packages mentioned in `package.json`:

```
  npm install
```

### Instructions
This project required modifying the `server.js` file and the `website/app.js` file. `index.html` was used for element references, and once finished with the project steps, `style.css` was used to style the application to customized perfection.

### Extras
If interested in testing the code, `tests.js` can be used as a template for writing and running some basic tests for your code.

## Development

* Add a `GET` route that returns the projectData object in your server code Then, add a `POST` route that adds incoming data to projectData

* Acquire API credentials from OpenWeatherMap [website](https://openweathermap.org/api)

* After the successful retrieval of the weather data, chain another Promise that makes a POST request to add the API data, as well as data entered by the user, to your app.

* Finally, chain another Promise that updates the UI dynamically

For details now how these functionalities have been implemented, refer the source code.

## Running the App

* Open terminal in the root directory and run the following command:
  ```
    npm run start
  ```
* The server will start on `http://localhost:3000/` in your browser.

## References

* API [docs](https://openweathermap.org/current)
* [Stack Overflow](https://stackoverflow.com/) for resolveing errors 