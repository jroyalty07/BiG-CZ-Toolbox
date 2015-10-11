
BiG-CZ-Toolbox
==============

Work on the python toolboxes for advanced access and interaction with the BiG CZ data services.

## Data Access Web Services for the BiGCZ

[Initial notes about common, relevant data web services.](Web_Services.md)

## IPython (Jupyter) notebook demos
- Using the [ODM2 REST API's](http://sis-devel.cloudapp.net/docs/) (web services) from Python. It uses Emilio's [Marchantaria Time Series data use case](https://github.com/ODM2/ODM2/tree/master/usecases/marchantariats). The notebook can be [viewed as rendered by Github](https://github.com/BiG-CZ/BiG-CZ-Toolbox/blob/master/ipynotebooks/ODM2RESTdemo_MarchantariaUseCase.ipynb), but with the glitch that the interactive, inline map is not rendered; for best results see the notebook as [rendered on nbviewer](http://nbviewer.ipython.org/github/BiG-CZ/BiG-CZ-Toolbox/blob/master/ipynotebooks/ODM2RESTdemo_MarchantariaUseCase.ipynb). It can be downloaded from either system. 8/8/2015.
- [Various demos from Emilio, presented at the BiG CZ project meeting at Stroud in October 2014.](https://github.com/BiG-CZ/BiG-CZ-Toolbox/tree/master/ipynotebooks/2014OctMeeting)

## Multi-platform, easy-to-install Python environment based on Conda

Will create a Python configuration based on the [Conda package management system](http://conda.pydata.org/docs/) ([Anaconda](https://store.continuum.io/cshop/anaconda/) is based on conda). Will connect to IOOS efforts, with conda recipes at https://github.com/ioos/conda-recipes and its linked anaconda (fomerly "binstar") channel at https://anaconda.org/ioos/. Or if it takes off, the broader [conda-forge](https://conda-forge.github.io/) effort.

[This Continuum blog post is a terrific, recent and comprehensive introduction to conda](http://www.continuum.io/blog/conda-data-science) targeted to data scientists. It also has links to a presentation (Youtube and slides) on the same material. An extra nifty aspect of this material is that it "explores how to use conda in a multi-language data science project" with an example combining Python and R libraries (conda now supports R as well).
