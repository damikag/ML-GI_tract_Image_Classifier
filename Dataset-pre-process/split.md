
#### Data-set

[KVASIR version 2](https://datasets.simula.no/kvasir/data/kvasir-dataset-v2.zip) is used wchich contains 8000 images.(1000 images for each class.)


###### 8 Classes of the data-set

Anatomical Landmarks:-
- Z-line
- Pylorus
- Cecum

Pathological Findings:-
- Esophagitis
- Polyps
- Ulcerative Colitis


Polyp Removals:-
- Dyed and Lifted Polyps
- Dyed Resection Margins

Data-set is shuffled using Linux ```shuf``` command and split into two as follows while preserving the data distribution.

Train set - 6400 images (800 images from each class)
Test set - 1600 images (200 images from each class)

Data-set is stored back in gdrive in order to load in to Google Colab when needed.