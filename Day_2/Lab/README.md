#Data curation with **Open Refine**

1. Open Refine Overview & Basics
2. Reconciliation
3. Publishing XML w/OpenRefine
4. Further Resources

##Vocabulary

- Normalization: from relational database design, "the process of organizing the attributes and tables of a relational database to minimize data redundancy."  More generally used to mean standardizing a dataset according to a controlled vocabulary or metadata schema.

- Faceting: filtering your dataset based on a particular text feature [link](https://github.com/OpenRefine/OpenRefine/wiki/Faceting)

- Clustering: The process of using an algorithm to group similar data together, and edit in bulk [link](https://github.com/OpenRefine/OpenRefine/wiki/Clustering)

- Reconciliation: "a semi-automated process of matching text names to database IDs (keys). This is semi-automated because in some cases, machine alone is not sufficient and human judgment is essential." [link](https://github.com/OpenRefine/OpenRefine/wiki/Reconciliation)


##1. Basics of Open Refine

General resources on Open Refine: [http://openrefine.org/](http://openrefine.org/)

Open Refine Wiki: [https://github.com/OpenRefine/OpenRefine/wiki](https://github.com/OpenRefine/OpenRefine/wiki)

### Dataset for this section

Data from the New York Public Library "What's on the Menu?" Project: [http://menus.nypl.org/](http://menus.nypl.org/) (Should be on your desktop as menus.csv)

##2. Reconciliation

###Biodiversity Reconciliation Services (from Rod Page's [iPhylo Blog](iphylo.blogspot.com/2012/02/using-google-refine-and-taxonomic.html))

- EOL: http://iphylo.org/~rpage/phyloinformatics/services/reconciliation_eol.php
- NCBI taxonomy: http://iphylo.org/~rpage/phyloinformatics/services/reconciliation_ncbi.php
- uBio FindIT: http://iphylo.org/~rpage/phyloinformatics/services/reconciliation_ubio.php
WORMS http://iphylo.org/~rpage/phyloinformatics/services/reconciliation_worms.php
- GBIF: http://iphylo.org/~rpage/phyloinformatics/services/reconciliation_gbif.php
- Global Names Index: http://iphylo.org/~rpage/phyloinformatics/services/reconciliation_globalnames.php

##Dataset for this section 

Custom dataset from [GBIF.org](http://www.gbif.org/).  Should be on your desktop as biodiversity.txt

##3. Publishing XML

Using NYPL dataset again; template should be on your desktop as template.txt

##Further Resources

**A quick note on the Freebase Reconciliation API:** Many Refine services rely/relied on this; however, Google has been slowly shutting Freebase down over the last year.  Developers are currently working on integration with Wikidata as a replacement, but there's no estimate on its availability.  That said, there are many tutorials available that use Freebase as a resource which may be worth exploring.

Freebase API services now available from: http://reconcile.freebaseapps.com/reconcile

Further information about [Freebase](www.freebase.org) integration with Open Refine [https://github.com/OpenRefine/OpenRefine/wiki/Reconciliation](https://github.com/OpenRefine/OpenRefine/wiki/Reconciliation)

Google on Freebase shut down: [link](https://plus.google.com/109936836907132434202/posts/bu3z2wVqcQc)

- Rod Page's full tutorial on taxonomic name reconciliation: [link](http://iphylo.blogspot.com/2012/02/using-google-refine-and-taxonomic.html)

- Cleaning Geo-Data in Open Refine (AKA georeferencing):[link](http://ahmadassaf.com/blog/data-analysis/cleaning-geo-data-open-refine/)

- Converting Spreadsheets into MODS XML through Open Refine: [link](https://www.utsc.utoronto.ca/digitalscholarship/content/blogs/converting-spreadsheets-modsxml-using-open-refine)

- More tutorials: [link](https://github.com/OpenRefine/OpenRefine/wiki/External-Resources)


###Advanced resources

- Google Refine "Cheat Sheet": [link](http://arcadiafalcone.net/GoogleRefineCheatSheets.pdf)

- GREL: [link](https://github.com/OpenRefine/OpenRefine/wiki/Variables)

- Clustering in depth: [link](https://github.com/OpenRefine/OpenRefine/wiki/Clustering-In-Depth)

##Acknowledgements

This NYPL portion of this exercise was created at the Maryland Institute for Technology in the Humanities and developed through the Digital Humanities Data Curation Institute series, generously funded by the National Endowment of the Humanities.  

Special thanks to Trevor Muñoz, Lydia Zvyaginsteva and Megan Senseney!


