---
title: Bringing the Generic Mapping Tools to Python
author: uieda, pwessel
date: 2017-07-13
repository: GenericMappingTools/scipy2017
slides: 10.6084/m9.figshare.7635833
event: Python in Science Conference
thumbnail: scipy2017.png
youtube: 93M4How7R24
alm: true
license: CC-BY
layout: publication
tags: pygmt, open-source
---

{% from "utils.html" import youtube_embed %}

# About

This was the first talk I gave about [GMT/Python](https://www.gmtpython.xyz), a
wrapper that [I'm building for the Generic Mapping
Tools][/blog/hawaii-gmt-postdoc].
I didn't have that much implemented yet but was able to give a quick demo.


# Video recording

Scipy records all of the presentations and [makes them available on
YouTube](https://www.youtube.com/playlist?list=PLYx7XA2nY5GfdAFycPLBdUDOUtdQIVoMf).
Here is the video of mine:

{{ youtube_embed("93M4How7R24") }}


# Slides

I made the slides in Google Drive. You can see them below or follow the link:

<div class="embed-responsive embed-responsive-4by3">
<iframe
src="https://docs.google.com/presentation/d/15he1klG9gCvBgGr3jGeQhTbcY5xShKv54l4BVnIxYBg/embed?start=false&loop=false&delayms=3000"
frameborder="0" width="960" height="749" allowfullscreen="true"
mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>


# Abstract

The Generic Mapping Tools (GMT) is an open-source software package widely used
in the geosciences to process and visualize time series and gridded data.
Maps generated by GMT are ubiquitous in scientific publications in areas such
as seismology and oceanography.
We present a new GMT Python wrapper library built by the GMT team.
We will show the design plans, internal implementations, and demonstrate an
initial prototype of the library.
Our wrapper connects to the GMT C API using ctypes and allows input and
output using data from numpy ndarrays and xarray Datasets.
The library is still in early stages of design and implementation and
we are eager for contributions and feedback from the Scipy community.