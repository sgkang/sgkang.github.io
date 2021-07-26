---
title: Research
layout: page
order: date
banner: aem_butte.png
banner_description: "Resistivity of the Butte County, California, U.S.A"
---

{% from "utils.html" import make_index, make_tags, make_tag, fa %}


My research uses computational methods in geophysical inversion and data science to advance the use of  applied geophysics in geoscience applications including groundwater, environmental, geotechnical, and minerals. Problems in these applications are multi-disciplinary requiring effective mechanisms such as open-source tools to communicate across disciplinary lines. Such tools are important to me, as I want to interact with people from both academia and industry to help solve these problems. I bring computational expertise as well as experience related to field acquisition particularly in electromagnetics (EM) and induced polarization (IP), but also I have a background in potential field methods such as gravity and magnetics. I am a developer of open-source computational tools (e.g. SimPEG — open-source geophysical software) and want to promote the growth of those open source tools as well as use them. 

# Grants

These are funded research projects in which I participate as a principal geoscientist:

<div class="research-index">
    {{ make_index(site.reflinks["/research"].content, site, hr=false, date=false) }}
</div>


# Research Themes

## XXX

XXX

<div class="research-index">
    {{ make_tags(["inversion", "gravity", "magnetic", "euler-deconvolution"], icon=true) }}
    {{ make_index(site.reflinks["/tag/inversion"].content[:4], site, hr=false, date=false) }}
</div>


## XXX

XXX

<div class="research-index">
    {{ make_tags(["forward-modeling", "tesseroids"], icon=true) }}
    {{ make_index(site.reflinks["/tag/forward-modeling"].content[:4], site, hr=false, date=false) }}
</div>


## XXX

XXX

<div class="research-index">
    {{ make_tags(["equivalent-layer"], icon=true) }}
    {{ make_index(site.reflinks["/tag/equivalent-layer"].content[:4], site, hr=false, date=false) }}
</div>


# Open-source software

X
XX
<div class="research-index">
    {{ make_tags(["open-source"], icon=true) }}
    {{ make_index(site.reflinks["/tag/open-source"].content[:4], site, hr=false, date=false) }}
</div>

I'm the creator and/or maintainer of the following projects:

<div class="research-index">
</div>


## SimPEG ([www.simpeg.xyz](https://www.simpeg.xyz))

XXX

* [Verde](https://www.fatiando.org/verde/): The first one I started working on. A
  library for gridding and spatial data processing.
* [Pooch](https://www.fatiando.org/pooch/): A small Python library that manages the
  download and caching of sample data sets. It will be used in support of the other
  packages.
* [RockHound](https://www.fatiando.org/rockhound/): Download common geophysical models
  and datasets (think PREM, CRUST1.0, ETOPO1) and load them into Python data structures.
* [Harmonica](https://www.fatiando.org/harmonica/dev/): Library for processing and
  modeling gravity and magnetic data.

<div class="research-index">
    {{ make_tags(["fatiando"], icon=true) }}
    {{ make_index(site.reflinks["/tag/fatiando"].content[:4], site, hr=false, date=false) }}
</div>

## EM GeoSci

Command-line programs for gravity forward modeling. This was my first software
project. I started working on *Tesseroids* in 2008 for my [Bachelor's thesis
project][/about/bachelors] and continued in collaboration with Professor [Carla
Braitenberg](https://www2.units.it/braitenberg/) from the [University of
Trieste](https://dmg.units.it/). The paper "[/papers/paper-tesseroids-2016]"
describes the algorithms behind [version
1.2.0](https://doi.org/10.5281/zenodo.16033) of the software, which ended up
becoming a chapter of my [PhD thesis][/about/phd].

<div class="research-index">
    {{ make_tags(["tesseroids"], icon=true) }}
    {{ make_index(site.reflinks["/tag/tesseroids"].content[:4], site, hr=false, date=false) }}
</div>

## GPG

A modern Python interface for the [Generic Mapping Tools](http://gmt.soest.hawaii.edu/).
I started building PyGMT (formerly GMT/Python) in 2017 as part of my
[postdoc at the University of Hawaii][/blog/hawaii-gmt-postdoc] with
[Paul Wessel](http://www.soest.hawaii.edu/wessel) (the co-creator and main developer of
GMT).
Work is still in early stages but there is a minimum working example on the
website. PyGMT was used to generate the bathymetry and topography banner
images for this website.

<div class="research-index">
    {{ make_tags(["pygmt"], icon=true) }}
    {{ make_index(site.reflinks["/tag/pygmt"].content[:4], site, hr=false, date=false) }}
</div>
