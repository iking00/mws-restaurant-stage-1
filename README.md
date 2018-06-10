# Restaurant Reviews
---

## Project Description

This site is being devloped as a part of the Udacity Front-End Web Developer Nanodegree.
The site is a listing of restaurants from select NY neighborhoods. It includes location and hours information of the restaurants as well as reviews.

### Dependencies
- Python
- Google Maps API Key


### How to start up local server

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`.

### Usage

- You should obtain your own Google Maps API Key and update index.html & restaurant.html files script src with it. [Google Maps API Key](https://developers.google.com/maps/documentation/javascript/get-api-key)
- The site should be kept responsive without the need for CSS frameworks.
- Accessibility should be considered while developing the site. [WAI-ARIA](https://www.w3.org/WAI/standards-guidelines/aria/)
- A service worker is included for relevant browsers to cache site assets. See sw/index.js.
  - To update cache increment `staticCacheName`. The service worker will cache files listed in the 'install' event and remove any prior caches.