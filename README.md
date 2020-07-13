[![CC BY 4.0][cc-by-shield]][cc-by]

# Linked Data 'n' Music

Some Jupyter notebooks (http://jupyter.org/) to explore music related datasets. To learn more about Jupyter notebooks, see this detailed tutorial: https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook#WhatIs

## Usage

### Run notebook online (interactive)
To run this repo online, click on the following Binder badge: 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/musicEnfanthen/linked-data-n-music/master)

Binder (https://mybinder.org/) provides a framework to run Jupyter notebooks online without the need to install the whole Jupyter Notebook environment (especially useful for classes, e-learning etc).

Another option would be Google Notebooks (not used here):
https://colab.research.google.com


### Run notebook locally

To run this repo on your local machine, make sure you have installed the following:

1. Python (Version 3.6): https://www.python.org/downloads/
    follow the instructions of the installer

2. Jupyter Notebook (http://jupyter.org/install)
    
    After installation of Python, open terminal and type (if needed change „python3“ to „python“):
    ```
    python3 --version
    python3 -m pip install --upgrade pip
    python3 -m pip install jupyter
    ```

After successfull installation, fork this repo and clone your fork to your local machine. 

To start the notebook server, change to the directory of your local clone in your terminal and type:
    
```
jupyter notebook
```

The server should be running now and the jupyter dashboard should open in your browser.

### Credits

The approach to use SPARQL in a Jupyter notebook is based on & inspired by [@Bob DuCharme](https://github.com/bobdc-ccri)'s blog entry: 
- http://www.bobdc.com/blog/jupytersparql/ 

and the corresponding notebook 

- https://github.com/bobdc/misc/blob/master/JupyterSPARQL/Jupyter%20and%20SPARQL%20and%20Dort%20or%20Dordrecht.ipynb.

It uses the `sparqlkernel` written and released by Paulo Villegas: https://github.com/paulovn/sparql-kernel.

### License
The notebooks in this repo are licensed under a [Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
