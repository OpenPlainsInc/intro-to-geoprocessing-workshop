# Intro to Geoprocessing Workshop

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tomorrownow/intro-to-geoprocessing-workshop/blob/main/ncssm_workshop.ipynb)

Introduction to geoprocessing with [GRASS GIS](https://grass.osgeo.org/) workshop.

## GRASS GIS Resources

* [GRASS Jupyter Docs:](https://grass.osgeo.org/grass83/manuals/libpython/grass.jupyter.html)
* [GRASS Python API Docs:](https://grass.osgeo.org/grass83/manuals/libpython/index.html)
* [GRASS C API Docs:](https://grass.osgeo.org/programming8/)
* [GRASS Tools:](https://grass.osgeo.org/grass83/manuals/general.html)
* [GRASS Add-ons:](https://grass.osgeo.org/grass83/manuals/addons/)

<!-- ![qr](./images/qr_code.png) -->

## Notebooks

* [ncssm_workshop.ipynb](ncssm_workshop.ipynb) - Workshop material for SMathHacks March 2nd, 2024
* [ncssm_data_prep.ipynb](ncssm_data_prep.ipynb) - Data preperation for SMathHacks workshop
* [geoprocessing.ipynb](geoprocessing.ipynb) - WIP

At the end of the workshop you will have create a web map showing a 5m flood innundation event at NCSSM.

[Workshop Web Map](https://tomorrownow.github.io/intro-to-geoprocessing-workshop/)

## Local Setup

Install GRASS GIS

[https://grass.osgeo.org/download/](https://grass.osgeo.org/download/)

```bsah
# clone the forked repository
$ git clone YOUR_FORKED_REPO_URL

# create a virtual environment
$ python3 -m venv venv
# activate the virtual environment
$ source venv/bin/activate

# install dependencies
(venv) $ pip install -r requirements.txt

```
