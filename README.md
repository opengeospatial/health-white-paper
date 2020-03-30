# White Paper template

## Content

This folder contains the text for the White Paper

* wp.adoc - the main White Paper document with references to all sections
* remaining adocs - each section of the White Paper document is in a separate document: follow directions in each document to populate
* figures - figures go here
* images - Image files for graphics go here. Image files for figures go in the "figures" directory. Only place in here images not used in figures (e.g., as parts of tables, as logos, etc.)

## Building

To produce the HTML of the White Paper run `asciidoctor -r asciidoctor-bibtex --safe -a data-uri -o ogc-health-white-paper.html wp.adoc`

To produce the PDF of the White Paper run `asciidoctor-pdf -r asciidoctor-bibtex --safe -o ogc-health-white-paper.pdf wp.adoc`
