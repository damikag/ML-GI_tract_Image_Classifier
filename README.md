# ML model to automate classification of anomalies in gastrointestinal tract using Deep Learning.

#### Introduction
At present Endoscopy (Endoscopy is a nonsurgical procedure used to examine a person's digestive tract. Using an endoscope, a flexible tube with a light and camera attached to it, doctors can view pictures of digestive tract on a color TV monitor.) is used to diagnose diseases associated with the gastrointestinal tract. Normal procedure is doctors watch the live video stream and diagnose manually. But it is quite inefficient and there is a high change to miss some anomaly. It highly depends on doctors' personal experience and expertise. A research done by WHO revels that 1.8 million people die annually because of GI tract diseases and 2.8 million new GI tract cancer cases are reported annually. This emphasizes the importance of make the diagnosis process efficient.

This project focuses on how to improve the diagnosis process using deep learning.

#### Data-set

[KVASIR](https://datasets.simula.no/kvasir/) data-set containing images from inside the gastrointestinal (GI) tract is used to conduct the project. The collection of images are classified into three important anatomical landmarks ,three clinically significant findings and two categories of images related to endoscopic polyp removal. Sorting and annotation of the data-set is performed by medical doctors ( experienced endoscopists).

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

[KVASIR version 2](https://datasets.simula.no/kvasir/data/kvasir-dataset-v2.zip) is used and it contains 8000 images.(1000 images for each class.)

Data-set is shuffled and split into two.
Train set - 6400 images (800 images from each class)
Test set - 1600 images (200 images from each class)