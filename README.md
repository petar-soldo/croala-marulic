# Exploring Marko Marulić

This is a fork of the CroALa repository, used for an exam project for the [Scripting Languages\[G0W95B\]](https://onderwijsaanbod.kuleuven.be/2025/syllabi/e/G0W95BE.html) course of the [Digital Humanities](https://www.kuleuven.be/programmes/master-digital-humanities) programme at [KU Leuven](https://www.kuleuven.be/english/kuleuven/).

## Scope and aim of the project

The main task of the project is to perform an "exploratory analysis of data" and "to (...) independently apply the programming techniques explored during the course".

For this purpose, *CroALa* was chosen as a dataset to be analyzed and Marko Marulić as an author of particular interest.

We set two goals for our project.

1. Perform a short analysis of the documents in _CroALa_ based on their metadata.
2. Perform a short text analysis of selected works by Marko Marulić.

This is the approximate workflow:

1. Create a Pandas dataframe with metadata from *CroALa* documents.
2. Explore and visualize *CroALa* metadata.
3. Extract and perfrom NLP processing of selected texts by Marko Marulić
4. Perform simple data analysis and visualiation using text annotations.

## Contents

The main file is [the Juypter notebook of the project](https://github.com/petar-soldo/croala-marulic/blob/master/croala-marulus.ipynb) containing all the code with comments, explanations and refrences.

Nice byproducts are the [metada data CSV](https://github.com/petar-soldo/croala-marulic/blob/master/croala_metadata.csv) file and [XLSX file](https://github.com/petar-soldo/croala-marulic/blob/master/croala_metadata.xlsx) where you can see the information extraxted from the XML files in a table view.

Analysis and visualisation of the metadata can be found in the notebook, but will, hopefully, be available as a standalone report. Same goes for analysis of Marulić's works.

---

Below you can find an abridged version of the original README.md:

> ## Croatiae auctores Latini - texts ##
>
>  [![DOI](https://zenodo.org/badge/36577371.svg)](https://zenodo.org/badge/latestdoi/36577371)
>
>TEI XML encoded Latin texts from the [Croatiae auctores Latini](https://croala.ffzg.unizg.hr) collection, freely available under a [CC-BY license](LICENSE.md).
>
>The files edited here are published as a [PhiloLogic 4](https://artfl-project.uchicago.edu/philologic4) collection [CroALa](http://solr.ffzg.hr/philo4/croala0/). 
>
>There is also a [BaseX](https://basex.org/) XML database (see an earlier analysis in [Quadrata rotundis](http://solr.ffzg.hr/dokuwiki/doku.php/z:crotyr-quadrata) paper). The BaseX XML db of CroALa is published through own simple text publishing and searching system on the CroALa site: [CroALa CDB](http://croala.ffzg.unizg.hr/cdb/index). For XQuery scripts, see the directories [croalabro](/scripts/croalabro) and [croalabro-xqm](/scripts/croalabro-xqm).
>
>* Address of this Git repo: on [Github](https://github.com/nevenjovanovic/croatiae-auctores-latini-textus)
>
>### Contents ###
>
>* The TEI XML texts are in [txts](/txts) directory
>* The word counts for files are in [croala-wordcounts.xml](croala-wordcounts.xml)
>* The scripts for a text publishing and searching system: [croalabro](/scripts/croalabro) and [croalabro-xqm](/scripts/croalabro-xqm)
>* The reading versions of documents are transformed from TEI XML source to XHTML in oXygen (with an additional XSL script: [html-add-class.xsl](scripts/xsl/html-add-class.xsl)) and served as static files in the local directory `basex/webapp/static/`
>* The CSS framework used is [Chota](https://jenil.github.io/chota/)
>* Additional scripts for the BaseX XML database: [xq](/scripts/xq)
>* The ODD and RNG validation: [schemas](/schemas)
>* The oXygen project file is [croalaproject.xpr](croalaproject.xpr)
>
>#### Current state of the collection ####
>On 2025-08-11 the collection contains:
>
>*  *569* TEI XML documents
>*  *5,817,677* words in texts (metadata and encodings are not counted)
>
>#### Editor ####
>
>* Neven Jovanović (nevenjovanovic), Department of Classical Philology, Faculty of Humanities and Social Sciences, University of Zagreb; [orcid.org/0000-0002-9119-399X](http://orcid.org/0000-0002-9119-399X)




