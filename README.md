# Restaurant Review Web App (part of Udacity's Mobile Web Specialist Certification Course)

A simple web app that shows reviews about restaurants in an area. Developed as part of Udacity's Front-End Developer Nanodegree course.
The aim of the project is to create a responsive web app with basic accessibility support, using pure HTML and CSS, without making use of frameworks like Bootstrap. Caching is also implemented by making use of a Service Worker.

A live demo can be found at [https://thedorkknightrises.github.io/mws-restaurant-stage-1/](https://thedorkknightrises.github.io/mws-restaurant-stage-1/)

Note: The data displayed is static and present in `data/restaurants.json` file.

### Instructions for running the site locally

1. In the root folder of the cloned repository, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.


