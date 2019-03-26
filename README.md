# DHd 2019 Workshop - Automatic Text and Feature Recognition: Mit READ Werkzeugen Texte erkennen und Dokumente analysieren
This repo contains the material for the session on Automatic Feature Recognition.

## Graphical content extraction using dhSegment



### Installation
We will make use of the tool [_dhSegment_](https://github.com/dhlab-epfl/dhSegment). 
To install it, follow the installation procedures as described in the 
[documentation](https://dhsegment.readthedocs.io/en/latest/start/install.html), and create a python environment.

We will also make use of a [Jupyter Notebook](https://jupyter.org/) to get through the steps and visualize the results.


### Downloads

__Images and annotations__

The [images](https://github.com/solivr/workshop_dhd19/releases/download/v.0.0/images.zip) used for this workshop are taken from Gallica, the digital library of the Bibliothèque Nationale de France (BnF). 
You'll find the identifiers and links in the `INFO.md` file in the downloaded `images` folder.

With their identifier, the images can be downloaded in full resolution using 
the [_Pyllica_](https://github.com/Dorialexander/Pyllica) tool.

The groundtruth annotations were produced by BnF's operators.

__Trained model__ 

The weights of the trained model can be downloaded 
[here](https://github.com/solivr/workshop_dhd19/releases/download/v.0.0/model_dropcap.zip).
