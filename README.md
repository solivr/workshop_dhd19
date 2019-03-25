# DHd 2019 Workshop - Automatic Text and Feature Recognition: Mit READ Werkzeugen Texte erkennen und Dokumente analysieren
This repo contains the material for the session on Automatic Feature Recognition.

## Graphical content extraction using dhSegment



### Installation
We will make use of the tool [_dhSegment_](https://github.com/dhlab-epfl/dhSegment). 
To install it, follow the installation procedures as described in the 
[documentation](https://dhsegment.readthedocs.io/en/latest/start/install.html), and create a python environment.

We will also make use of a [Jupyter Notebook](https://jupyter.org/) to get through the steps and visualize the results.


### Sources

__Images and annotations__

The [images](https://github.com/solivr/workshop_dhd19/releases/download/v.0.0/images.zip) used for this workshop are taken from Gallica, the digital library of the Bibliothèque Nationale de France (BnF). 
They can be found with the following identifiers :

Drop-cap:
* [btv1b86000847](https://gallica.bnf.fr/ark:/12148/btv1b86000847)
* [btv1b86001190](https://gallica.bnf.fr/ark:/12148/btv1b86001190)
* [btv1b55007627b](https://gallica.bnf.fr/ark:/12148/btv1b55007627b)
* [btv1b8626366r](https://gallica.bnf.fr/ark:/12148/btv1b8626366r)
* [btv1b8624646d](https://gallica.bnf.fr/ark:/12148/btv1b8624646d)
* [btv1b86001798](https://gallica.bnf.fr/ark:/12148/btv1b86001798)
* [btv1b8609577m](https://gallica.bnf.fr/ark:/12148/btv1b8609577m)
* [btv1b86001494](https://gallica.bnf.fr/ark:/12148/btv1b86001494)
* [btv1b86256422](https://gallica.bnf.fr/ark:/12148/btv1b86256422)
* [btv1b86000439](https://gallica.bnf.fr/ark:/12148/btv1b86000439)
* [btv1b8600005m](https://gallica.bnf.fr/ark:/12148/btv1b8600005m)
* [btv1b7300366d](https://gallica.bnf.fr/ark:/12148/btv1b7300366d)
* [bpt6k1510172g](https://gallica.bnf.fr/ark:/12148/bpt6k1510172g)

The images can be downloaded in full resolution using the tool [_Pyllica_](https://github.com/Dorialexander/Pyllica).

The groundtruth annotations were produced by BnF's operators.

__Trained model__ 

The weights of the trained model can be downloaded 
[here](https://github.com/solivr/workshop_dhd19/releases/download/v.0.0/model_ornaments.zip).
