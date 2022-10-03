# Interacting and Other Catalogues
This repository contains the results of a three month project at the European Space Astronomy Centre in Madrid. This project focused on looking through the Hubble Source Catalogue for interacting galaxies using ESA: Datalabs to do a direct exploration of the Hubble Science Archives. This exploration was conducted using the convolutional neural network Zoobot. 21,792 interacting systems or galaxies were found in this way. Multiple other objects of interest were also found in the contamination of the sample. These have been split into further catalogues. Definitions for each catalogue title can be found below. Each file contains a Source ID - this is identical to the Hubble Source Catalogue's SourceID. They contain the right ascension and declination (in the FK5 frame) of each source in decimal degrees. They also contain whether a reference for each source has been found in SIMBAD as an indication of whether the source has been looked at before. If it has been referenced, then a list of at most two references is provided. This was done using the Astroquery.simbad Python package. 

## Main Catalogue
* interacting-catalogue.csv - The catalogue of interacting galaxies. Contains 21,792 systems. 7,523 referenced, 14,404 unreferenced.

## Other Catalogues
The below catalogues are all systems which Zoobot scored highly to be interacting galaxies, but were in fact another type of system. We have broken them down here into difference catalogues.

* agn-catalogue.csv - Catalogue of systems containing AGN found. Contains 35 systems. 21 referenced, 14 unreferenced.
* groups-catalogue.csv - Catalogue of systems which were classes as `Galaxy Groups'. Contains 6 systems. 6 referenced, 0 unreferenced.
* high_z-catalogue.csv - Catalogue of systems which had strange morphologies due to being very high redshift. Contains 10 systems. 7 referenced, 3 unreferenced.
* jellyfish-catalogue.csv - Catalogue of systems which were jellyfish galaxies. Contains 18 systems. 5 referenced, 13 unreferenced.
* jets-catalogue.csv - Catalogue of systems which contained jets. Contains 25 systems. 10 referenced, 15 unreferenced.
* lenses-catalogue.csv - Catalogue of systems which were actually gravitational lenses. Contains 189 systems. 57 referenced, 132 unreferenced.
* ly-catalogue.csv - Catalogue of systems which were classified on SIMBAD as Lyman-Break/Lyman Alpha galaxies. Contains 1 system. 1 referenced, 0 unreferenced.
* overlap-catalogue.csv - Catalogue of systems which were not interacting, but had two galaxies overlapping by projection effects. Contains 221 systems. 92 referenced, 129 unreferenced.
* planetary-catalogue.csv - Catalogue of systems which were edge-on protoplanetary disks. Contains 9 systems. 2 referenced, 7 unreferenced.
* radio-catalogue.csv - Catalogue of systems which were radio galaxies. Contains 1 system. 1 referenced, 0 unreferenced.
* rings-catalogue.csv - Catalogue of systems which were ringed galaxies. Contains 6 systems. 1 referenced, 5 unreferenced.
* submillmitre-dusty-catalogue.csv - Catalogue of systems which had very large dust lanes or were submillimetre galaxies. Contains 11 systems. 8 referenced, 3 unreferenced. 
* supernova-catalogue.csv - Catalogue of systems which were supernova remnants. Contains 4 systems. 3 referenced, 1 unreferenced.
* unknown-catalogue.csv - Catalogue of systems which could not be classified in this work. These systems are unknown. Contains 6 systems. 0 referenced, 6 unreferenced.
* ysc-catalogue.csv - Catalogue of systems which were young stellar clusters. Contains 1 system. 1 referenced, 0 unreferenced.
* yso-catalogue.csv - Catalogue of systems which were young stellar objects. Contains 2 systems. 1 referenced, 1 unreferenced.
