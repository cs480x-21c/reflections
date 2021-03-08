# Overview

The visualization I chose to reflect on this week is the globe visualization on Github's [home page](github.com). It is a continuously rotating globe that visualizes recent Github pull requests. Worth noting is that it can only be seen on the Github home page that you see if you are not logged in, so to experience it you will need to sign out.

# Background

Github themselves actually wrote up a blog post about how they created the globe that can be found [here](https://github.blog/2020-12-21-how-we-built-the-github-globe/). It is implemented using three.js, which in turn uses WebGL. three.js is a popular JavaScript library for visualizing 3D graphics in the browser. The visualization consists of five parts:
* A halo around the globe
* The globe itself
* The earth's landmasses
* Blue spikes for open pull requests
* Pink arcs for merged pull requests

In order to run on a wide range of devices, the globe also features four different quality levels. These reduce factors such as the resolution and number of pull requests being drawn so as to perform better on low-end devices. Additionally, when the globe first loads it uses IP geolocation to look up where the user is and center the globe on that geographic location to start.

# Conclusion

Overall, this is a great example of visualizing live data that I suspect many of us have actually encountered before. Admittedly, it is not very useful for anything other than gawking at, but it is a very well-made and aesthetically pleasing visualization. It is somewhat technically impressive too, especially when we consider the sheer volume of data that Github has to take in and filter through to find good pull requests to show on the globe.
