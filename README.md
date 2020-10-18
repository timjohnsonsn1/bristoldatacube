# Bristol Data Cube
## Introduction
Hi! My name is Tim Johnson and by day I am a delivery manager at [Scott Logic](https://www.scottlogic.com/).  The CTO of Scott Logic (Colin Eberhardt) is [passionate about open source](https://www.finos.org/blog/colin-eberhardt-why-i-open-source) and encourages others to get involved.  I’ve had the opportunity to work on one of Scott Logic’s open source projects ([DataHelix](https://blog.scottlogic.com/2020/08/06/datahelix-intro.html)), which has inspired me to have a go at contributing to something in my spare time.  But what should I choose?

I’ve always had an interest in space and have a degree in Physics.  After a period of searching I came across the [Open Data Cube](https://www.opendatacube.org/):

*"The ODC seeks to increase the value and impact of global Earth observation satellite data by providing an open and freely accessible exploitation architecture. The ODC project seeks to foster a community to develop, sustain, and grow the technology and the breadth and depth of its applications for societal benefit."*

The Open Data Cube ticks all my boxes:
- There is real value in the end product, as tool to help with sustainable development across the planet
- There is an active community working on this
- There is a space / physics angle
- The implementation technology is relevant to my job

My goal is to become an active contributor.  This is a slow-burn thing, I've got a lot to learn, and not a huge amount of free time, but I find it all very interesting and I hope to be able to contribute code / fixes to something that is helping a lot of people with their earth observation work.

## Purpose
The purpose of the Bristol Data Cube is to have a relatively small geographic area on which to practice installing, running and using ODC.  (The very first run will be of the Wotton-under-Edge area).

## Example uses
Through playing in the ODC [sandbox](https://docs.dea.ga.gov.au/setup/sandbox.html) and a bit of internet trawling I’ve seen these potential uses of ODC that could be relevant to the UK:

### Coastline mapping
The UK Hydrographic Office has been using satellite data for [updating their coastline maps](https://ukhodigital.blog.gov.uk/2020/02/12/creating-coastlines-using-data-science/).  It looks like there is significant overlap with the [contour extraction capability](https://docs.dea.ga.gov.au/notebooks/Frequently_used_code/Contour_extraction.html) of ODC, which has been used to [monitor coastal erosion along Australia’s coastline](https://docs.dea.ga.gov.au/notebooks/Real_world_examples/Coastal_erosion.html).

### Forestry
[DEFRA has got an interest](https://defradigital.blog.gov.uk/2017/03/21/the-satellites-that-safeguard-our-forests/) in satellite data for forestry, again it looks similar to an [Australian forestry use case](https://docs.dea.ga.gov.au/notebooks/Real_world_examples/Change_detection.html).

### Agriculture
[Example](https://twitter.com/AgricultureData/status/1306166262796611584) of ODC data being used to look at crop health.

### Assessing land use
[This](https://twitter.com/USGSLandsat/status/1309173412510793737?s=09) example shows the dramatic change in land use in Northern Paraguay, further information [here](https://landsat.visibleearth.nasa.gov/view.php?id=92078).

### Biodiversity monitoring
The [Joint Nature Conservation Committee](https://jncc.gov.uk/about-jncc/) (JNCC) is working with Natural England to provide [biodiversity maps](https://jncc.gov.uk/monitoring/analyses-trends/).

Could ODC illustrate the progress that is being made in [rewilding the Scottish Borders](https://www.rewildingbritain.org.uk/rewilding/what-does-rewilding-look-like)?

## Current progress
So where have I got so far?  I’ve installed datacube on a Centos 8 virtual machine and have successfully added the [Landsat 8 product definition file](https://github.com/opendatacube/datacube-core/blob/develop/docs/config_samples/dataset_types/ls8_scenes.yaml).  My next step is to produce the [Dataset Document](https://datacube-core.readthedocs.io/en/latest/ops/indexing.html#dataset-documents).
