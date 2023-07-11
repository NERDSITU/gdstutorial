# Geospatial Data Science Tutorial for IC2S2'23

This is the resource page for the [Geospatial Data Science Tutorial](https://www.ic2s2.org/tutorials.html#geospatial) for the [9th International Conference on Computational Social Science (IC2S2'23)](https://www.ic2s2.org/), July 17th, 2023 in Copenhagen.

## 💻 Preparations

*Before the tutorial*, install `gds_py` (version 9.0) from `gds_env`: [https://darribas.org/gds\_env/stacks/gds\_py/#install](https://darribas.org/gds_env/stacks/gds_py/#install)

We recommend using the Docker image according to the [instructions](https://darribas.org/gds_env/guides/docker_install/), but a conda version is also available. The Docker image will require 4 GB of storage space.

When done with the installations, test that the notebook [installtest.ipynb](installtest.ipynb) runs without errors. We will use its imported libraries during the tutorial.

## 🕹️ Running the notebooks

After preparations:  

1. Clone this repository to download the Jupyter notebooks to your own machine:

```
git clone https://github.com/NERDSITU/gdstutorial
```

2. In your terminal window, navigate to the folder with the course materials (`gdstutorial`)  

3. Run the Docker image from the terminal:

```
docker run --rm -ti -p 8888:8888 -v ${PWD}:/home/jovyan/work darribas/gds_py:9.0
```

4. You can now run the Jupyter notebooks using either Jupyter in the browser (use the link printed in your terminal window) or with your code editor of choice. If in Visual Studio Code, choose `Select kernel` > `Existing Jupyter Server` and the server name will appear.

## 📅 Schedule

| July 17, 2023 | Part | Topic |
|--------------:|:-----|-----------|
| 09:00 - 09:05 |  0. Introduction |        Introduction  |
| 09:05 - 09:40 |  1. Data Handling |        Data & Geometry, CRS, Libraries  |
| 09:40 - 09:50 |  |        *10 min break*  |
| 09:50 - 10:30 |  2. Spatial Statistics |        Choropleth Maps, Spatial Autocorrelation  |
| 10:30 - 11:00 |   |        *30 min break*  |
| 11:00 - 11:35 |  3. OpenStreetMap |        Introduction to OSM & OSMnx  |
| 11:35 - 11:45 |   |        *10 min break*  |
| 11:45 - 12:30 |  4. Spatial Networks |        Spatial Networks with Geopandas  |

<!-- - schedule markdown table +links to materials -->

## 🧑‍🏫 About us

We come from the research group [**NERDS**](<https://nerds.itu.dk/>) (NEtwoRks, Data & Society), Computer Science Department, IT University of Copenhagen.

[**Michael Szell**](<http://michael.szell.net/>) is associate professor in Data Science at IT University of Copenhagen, and external researcher at ISI Foundation and at the Complexity Science Hub Vienna. His research quantifies the patterns behind interlinked human behavior and human-built structures through mining large-scale data sets. He follows an anti-disciplinary approach using methods from data science and network science. Michael's current focus is on sustainable urban mobility and urban data science. He has also developed several interactive data visualization platforms such as What the Street!?, and the award-winning massive multiplayer online game Pardus.

[**Ane Rahbek Vierø**](https://anerv.github.io/) is a PhD student at department of Computer Science at the ITU University of Copenhagen. She is researching bicycle networks with a focus on transport equity and urban/rural divides in cycling accessibility. Ane has a background in urban geography and geographic information science and is combining methods and insights from urban planning, geospatial data science and mobility studies in her work.

[**Anastassia Vybornova**](https://github.com/anastassiavybornova) is a PhD fellow in Data Science at the IT University of Copenhagen. The goal of her PhD project is to support the sustainability shift of human mobility by means of data- driven bicycle network planning. Anastassia has a multidisciplinary background in Transcultural Communication, Technical Physics, and Environmental Science.

**Get in touch:** Michael Szell: <misz@itu.dk> • Anastassia Vybornova: <anvy@itu.dk> • Ane Rahbek Vierø: <anev@itu.dk>

## 📚 Resources

This tutorial is based on materials from our course in Geospatial Data Science, offered as part of the ITU master in data science: <https://github.com/mszell/geospatialdatascience>

For a general introduction to Geospatial Data Science in Python, we recommend the book and course materials by Rey, Arribas-Bel and Wolf:

* [Geographic Data Science with Python](<https://geographicdata.science/book/intro.html>) (book)
* [Geographic Data Science](https://darribas.org/gds_course/content/home.html) (course)

See also the excellent introductions to geographic data analysis with Python by Tenkanen, Heikinheimo, Aagesen and Fink:

* [Automating GIS Processes](<https://autogis-site.readthedocs.io/en/latest/>)

<!-- Add resources specifically for the intro part (Geopandas, map projections, choropleths, etc) -->

<!-- Add resources specifically for osm and osmnx) -->

### OpenStreetMap

* [OpenStreetMap (OSM)](https://www.openstreetmap.org/)
* [OSM Wiki](https://wiki.openstreetmap.org/wiki/Main_Page)
* [OSMnx tutorials](https://github.com/gboeing/osmnx-examples)
* [Introduction to the OSM data model](https://alga.win.tue.nl/tutorials/openstreetmap/)

### Spatial Networks

* [GeoPandas](https://geopandas.org) python library
* [GTFS](https://gtfs.org) - General Transit Feed Specification
