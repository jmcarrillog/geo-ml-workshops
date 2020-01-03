# Workshops on Machine Learning for Geospatial Data

These two workshops provide an introduction to some Machine Learning tools for the analysis of Geospatial data. The workshops are held in collaboration between the [Geospatial Centre](https://uwaterloo.ca/library/geospatial/) and the [Geospatial Club](https://www.facebook.com/uwgeospatial/) at the University of Waterloo.

Both workshops were prepared in the Winter 2019 term by Juan Carrillo and Jaydeep Mistry. Slides and code are published here in pdf and Jupyter nootebooks formats. We recommend you to try out the code within Kaggle, the [first](https://www.kaggle.com/jrmistry/uwgeo-club-ml-for-vector-geodata-workshop-1) and [second](https://www.kaggle.com/jcarrillo/machine-learning-for-geospatial-data-workshop-2a) notebooks are available as kernels for you to fork and re-run them.

## First workshop: Preventing traffic accidents in Toronto

The dataset is a table titled "Killed or Seriously Injured" (KSI) from the [City of Toronto's Police Open Data portal](http://data.torontopolice.on.ca/pages/open-data). It contains registries of all traffic collisions between 2007 and 2017 where a person was injured or property damage was reported.

Available as Kaggle [Kernel](https://www.kaggle.com/jrmistry/uwgeo-club-ml-for-vector-geodata-workshop-1). The [nootebook](/geo-ml-workshop-1-vector-data.ipynb) for this workshop includes:

* Exploratory data analysis through visualizations

<img src="/readme-images/toronto-accidents-time-series.png" width="500" /> <img src="/readme-images/toronto-accidents-heatmap.png" width="300" />

* Implementation of a Random Forest model to predict fatal accidents

## Second workshop: Understanding land use in the Amazon rain forest

The dataset is published by [Planet](https://www.planet.com/) and is part of a [Kaggle competition](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space/data) targeted at classification of high-resolution satellite images from the Amazon rain forest. It includes more than 40,000 image chips sampled over the area of interest.

Available as Kaggle [Kernel](https://www.kaggle.com/jcarrillo/machine-learning-for-geospatial-data-workshop-2a). The [nootebook](/geo-ml-workshop-2-raster-data.ipynb) for this workshop includes:

* Exploratory data analysis through visualizations

<img src="/readme-images/example-amazon-image.png" width="750" />

* Implementation of a Convolutional Neural Network for multi-label image classification

<img src="/readme-images/cnn-performance.png" width="700" />

## Attendees

Each workshop had a turnaround of about 30 attendees. Thanks to everyone for coming, asking interesting questions, and giving us feedback.

<img src="/readme-images/attendees-workshop-1.jpg" width="400" /> <img src="/readme-images/attendees-workshop-2.jpg" width="400" />

## Acknowledgments

Special thanks to Eva Dodsworth and Markus Wieland at the University of Waterloo Geospatial Centre for their collaboration on helping us organize these workshops.
