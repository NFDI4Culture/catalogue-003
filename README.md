## Objekte des Badisches Landesmuseums

## Part of the series: Austellungen des Badischen Landmuseum

[Programme instructions](https://nfdi4culture.github.io/class-ADA-CP-pipeline/)

2023-03-17 v1.0

![Italian Painting](6780765/Cupido.jpg)

Dieses SPARQL-Query wird verwendet, um eine Liste von Objekten abzurufen, die von dem Badischen Landesmuseum ausgestelt werden.

Example publications:

- [Exhibition catalogue demo: toc Baroque /toc](https://nfdi4culture.github.io/experimental-books-workshop/) from Experimental Books – Re-imagining Scholarly Publishing, COPIM. Workshop URL: https://experimentalbooks.pubpub.org/programme-overview

- [Publishers catalogue demo: ScholarLed](https://simonxix.github.io/scholarled_catalogue/) A catalogue of ScholarLed presses built on a Quarto / Jupyter Notebook model for computational publishing. The publication is automatically updated daily to reflect any new books added by the publishers.

- [Proof of concept #1](https://nfdi4culture.github.io/cp4c/) - Computational Publication: Computational Publishing for Collections - ADA CP Prototype #1 - Nov 22

- [Proof of concept #2](https://nfdi4culture.github.io/art_catalogue_test/) - To be confirmed, completion for end of April 2023. This contains all parts fully rendered: Cover, colophon, essay, collection, graph, TIB AV Portal, Semantic Kompakkt

- semanticClimate: To be confirmed - customised research papers readers made for regional climate change action plans based on IPCC reports and sourcing content from open research repositories.

- FSCI Summer School - publishing from collections class: To be confirmed, July 2023

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a> This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

Book cover: Reworking of [Baroque pearl with enamelled gold mounts set with rubies](https://en.wikipedia.org/wiki/File:Pendant_in_the_form_of_a_siren_MET_DT7173.jpg). Creative Commons CC0 1.0 Universal Public Domain Dedication. This file was donated to Wikimedia Commons as part of a project by the Metropolitan Museum of Art.

## Quarto and Jupyter Notebook

The main publishing workflow uses Quarto to render the output of Jupyter Notebook files. Run the .ipynb files in JupyterLab or Visual Studio Code or any other Jupyter environment and then run:

`quarto render`

for Quarto to render the output into an output directory, in this case, ./docs. 

GitHub Pages then serves the HTML files in the ./docs directory as a website. 
