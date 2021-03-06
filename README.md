# Introduction
This visualization demonstrates Wi-Fi usage at MIT throughout the given day. Each blue circle in the visualization represents a Wi-Fi access point on campus. The area of the circle is proportional to the number of users connected to the access point at a given time.

The data being used is at [util/data.csv](https://github.com/hariharsubramanyam/mit-wifi-data-vis/blob/master/util/data.csv). It consists of (timestamp, num_connected, id, longitude, latitude) tuples. 

# Demo

Go to [wifi.firebaseapp.com](http://wifi.firebaseapp.com).
# Usage

1. Install dependencies with `bower install`. To do this, you need to have [bower](http://bower.io/).
2. Launch an HTTP Server to serve static files in this directory: `python -m SimpleHTTPServer` (if you are on Python 3, use `python -m http.server`).
3. Navigate your browser to `http://localhost:8000/`

![Screenshot](https://raw.githubusercontent.com/hariharsubramanyam/mit-wifi-data-vis/master/images/screenshot.png)
