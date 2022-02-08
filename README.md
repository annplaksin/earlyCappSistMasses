# Collected metadata for masses in the early Cappella Sistina choirbooks

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6006654.svg)](https://doi.org/10.5281/zenodo.6006654)

## About

This repository contains a collection of metadata about the early Cappella Sistina choirbooks, once belonging to the Papal Chapel.
It presents the mass compositions contained in the manuscript sources V-CVbav MS 14, 23, 35, 41, 49, 51, 63, 197, 64 and concordant sources of these.

The data has been collected in the year 2015 and hasn't been double-checked by any other person. Even though the data was collected as conscientiously as possible, it is sometimes incomplete and errors are also possible. The data as well as the data structure has been collected mostly in German.
References for this metadata collection can be found under `./references`.

This data has been used already in:

* Plaksin, Anna Viktoria Katrin: "Modelle zur computergestützten Analyse von Überlieferungen der Mensuralmusik. Emprische Textforschung im Kontext phylogenetischer Verfahren.", Münster, 2021 (Schriften zur Musikwissenschaft aus Münster 27), online: [urn:nbn🇩🇪hbz:6-59029717067](http://nbn-resolving.de/urn:nbn:de:hbz:6-59029717067), DOI: [10.26083/tuprints-00017211](https://doi.org/10.26083/tuprints-00017211).

## Contents

The original SQLite database set is found under `./sql`. It contains not only the tables but various views for a better overview.
For opening and viewing the sql data, tools like e.g. the [DB Browser for SQLite](https://sqlitebrowser.org/) can be used.

The `./csv` folder contains csv exports of the tables and views.

In `./networkData` contains the relations of works and sources as bipartite network in `.csv` format. The edges are available as edge list or as adjacency matrix. The node list contains very basic information necessary for identification. Please note, this is the raw exported data for analysis.
