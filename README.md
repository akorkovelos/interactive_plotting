# interactive_plotting
Jupyter notebook showcasing how to generate interactive maps for key geospatial data formats using geopandas &amp; Folium

## Content

- **Interactive Mapping.ipynb** contains the core code
- **Datasets** directory contains sample input data for testing including:
	- Somaliland_adm1.gpkg
        - Somaliland_top_20_cities.gpkg
	- Somaliland_HF_WHO.gpkg
	- Ethiopia_interconnection.gpkg
        - Somaliland_GHI_10km.tif
- **maps** directory contains sample output map 
- **geospatial_env.yml** dependencies info in yalm for setting up the environment

## Setting up the environment & running the model

**Install from GitHub**

Download repository directly or clone it to you designated local directory using:

```
git clone https://github.com/akorkovelos/interactive_plotting.git
```

**Requirements**

The notebook has been developed in Python 3. We recommend installing [Anaconda's free distribution](https://www.anaconda.com/distribution/) as suited for your operating system. 

Once installed, open anaconda prompt and move to your local "gep_health_facilities" directory using:

```
> cd ..\interactive_plotting
```

In order to be able to run the notebook you should either install necessary packages or the environment. You can do this using the yml file as follows:

```
conda env create -f geospatial_env.yml
```

Once completed, you can now move to the directory and start a "jupyter notebook" session by simply typing:

```
..\interactive_plotting> jupyter notebook 
```


## Sample output

The sample output of this exersice is located in the maps directory at html. You may also find it online [here](https://datapane.com/u/alexandros/reports/somaliland-test-map)


## Credits

**Conceptualization & Development :** [Alexandros Korkovelos](https://github.com/akorkovelos)<br>
**Funding:** The World Bank

