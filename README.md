[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NFDI4Culture/experimental-books-workshop/HEAD)

# Experimental Books Workshop Catalogue

This repository contains materials for the Publishing from Collections: Introducing Computational Publishing for Culture workshop organised by Dr. Simon Worthington (Open Science Lab, TIB Hannover) for the [Experimental Books - Re-imagining Scholarly Publishing](https://experimentalbooks.pubpub.org/) conference held online on 2023-02-20.

Computational publishing was developed in the life sciences and STEM subjects to allow publishers and authors to embed executable code, visualisations and advanced media objects alongside conventional text in a document. This hands-on workshop demonstrates one way how humanities scholars might use computational publishing.

During the workshop, we will auto-compile catalogue publications for exhibitions or publication listings from multiple open data sources; and show how such compilations can be published multi-format: web, PDF, ebook, etc. A series of exercises, using Jupyter Notebooks for code and the Quarto platform to wrap up the notebooks for multi-format outputting, will give participants a practical introduction to some of the tools, possibilities and concepts of computational publishing.

## Workshop schedule

Full workshop schedule available at https://nfdi4culture.github.io/workshop-publishing-from-collections/

## Quarto and Jupyter Notebook

The main publishing workflow uses Quarto to render the output of Jupyter Notebook files. Run the .ipynb files in JupyterLab or Visual Studio Code or any other Jupyter environment and then run:

`quarto render`

for Quarto to render the output into an output directory, in this case, ./docs. 

GitHub Pages then serves the HTML files in the ./docs directory as a website. 
