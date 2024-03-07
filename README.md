# To bee or not to bee

This repository was intended to house a dataset consisting of beehive noise recordings and associated annotations, compiled for the purpose of developing a means of automated beehive noise recognition.

However, size limits on file uploads to GitHub prevented me from uploading the audio files which represented a majority of the original dataset, so the files included in this repository consist only of the associated text annotation files.

## Description

### Audio recordings [1]

#### *PLEASE NOTE: Limits on upload file size prevented me from including audio files described below in this repository*

The annotated dataset was developed based on a selected set of recordings acquired in the context of two different projects: the Open Source Beehive (OSBH) project and the NU-Hive project. Both projects main goal is to develop a beehive monitoring system capable of identifying and predict certain events and states of the hive that are of interest to the beekeeper. Among many different variables that can be measured and that help the recognition of different states of the hive, the analysis and use of the sound the bees produce is a big focus for both projects.

The recordings from the OSBH project were acquired through a citizen science initiative which asked people from the general public to record the sound from their beehives together with the registering of the hive state at the moment. Because of the amateur and collaborative nature of this project, the recordings from the OSBH project present great diversity due to the very different conditions in which the signals were acquired: different recording devices used, different environments where the hives were placed, and even different position for the microphones inside the hive. This variety of settings makes this dataset a very interesting tool to help evaluate and challenge the methods developed.

The NU-Hive project is a comprehensive effort of data acquisition, concerning not only sound, but a vast amount of variables that will allow the study of bees behaviors and other unknown aspects. The selected recordings are taken from 2 hives and labeled regarding two states: queen bee is present, and queen bee not present. Contrary to the OSBH project recordings, the recordings from the NU-Hive project are from a much more controlled and homogeneous environment. Here the occurring external sounds are mainly traffic, car honks and birds.

### The annotated dataset [1]

For each selected recording, time segments are labeled as Bee or noBee depending on the perceived source of the sound signal being from bees or external to the hive.

The whole annotated dataset consists of 78 recordings of varying lengths which make up for a total duration of approximately 12 hours of which 25% is annotated as noBee events.

About 60% of the recordings are from the NU-Hive dataset and represent 2 hives, the remaining are recordings from the OSBH dataset and 6 different hives. The recorded hives are from 3 main locations: North America, Australia and Europe.

 

### Annotation procedure [1]

The annotation procedure consists in hearing the selected recordings and marking the beginning and the end of every sound that could not be recognized as a beehive sound. The recognition of external sounds is based primarily on the perceived heard sounds, but a visual aid is also used by visualizing the log-mel frequency spectrum of the signal. All the above are functionalities offered by the Sonic Visualiser software, which was used by two volunteers that are neither bee-specialists nor specially trained in sound annotation tasks.

By marking these pairs of moments corresponding to the beginning and end of external sound periods, we are able to get the whole recording labeled into Bee and noBee intervals. Thus in the resulting Bee intervals only pure beehive sounds, (no external sounds) should be perceived for the entirety of the segment. The noBee intervals refer to periods where an external sound can be perceived (superimposed to the bee sounds).


## Authors [1]

Nolasco, Inês (Queen Mary University of London)
 
Benetos, Emmanouil (Queen Mary University of London)


## License [1]

This recommended license for this project is the Creative Commons Attribution 4.0 International License. The Creative Commons Attribution license allows re-distribution and re-use of a licensed work on the condition that the creator is appropriately credited.


## Acknowledgments

This dataset and its associated metadata was compiled and created by Inês Nolasco and Emmanouil Benetos from Queen Mary University of London. All credit for the content here displayed goes to Nolasco and Benetos.



[1] Nolasco, I., & Benetos, E. (2018). To bee or not to bee: An annotated dataset for beehive sound recognition [Data set]. Zenodo. 
 https://doi.org/10.5281/zenodo.1321278

## File Index

### Beehive Noise - Text File  Annotations
* Annotations - Sound Inside a Swarming Bee Hive  -25 to -15 minutes-sE02T8B2LfA.lab
* Annotations - Sound Inside a Swarming Bee Hive +5 to +15 minutes-BIZx-8kLrdw.lab
* Annotations Master.mlf
* CF001 - Missing Queen - Day -.lab
* CF003 - Active - Day - (214).lab
* CF003 - Active - Day - (215).lab
* CF003 - Active - Day - (216).lab
* CF003 - Active - Day - (217).lab
* CF003 - Active - Day - (218).lab
* CF003 - Active - Day - (219).lab
* CF003 - Active - Day - (220).lab
* CF003 - Active - Day - (221).lab
* CF003 - Active - Day - (222).lab
* CF003 - Active - Day - (223).lab
* CF003 - Active - Day - (224).lab
* CF003 - Active - Day - (225).lab
* CF003 - Active - Day - (226).lab
* CF003 - Active - Day - (227).lab
* CJ001 - Missing Queen - Day -  (100).lab
* CJ001 - Missing Queen - Day -  (101).lab
* CJ001 - Missing Queen - Day -  (102).lab
* CJ001 - Missing Queen - Day -  (103).lab
* CJ001 - Missing Queen - Day -  (104).lab
* GH001 - Active - Day - 141022_0659_0751.lab
* Hive1_12_06_2018_QueenBee_H1_audio___15_00_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___15_10_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___15_20_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___15_30_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___15_40_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___16_00_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___16_10_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___16_20_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___16_30_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___16_40_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___16_50_00.lab
* Hive1_12_06_2018_QueenBee_H1_audio___17_00_00.lab
* Hive1_31_05_2018_NO_QueenBee_H1_audio___15_00_00.lab
* Hive1_31_05_2018_NO_QueenBee_H1_audio___15_10_00.lab
* Hive1_31_05_2018_NO_QueenBee_H1_audio___15_20_00.lab
* Hive1_31_05_2018_NO_QueenBee_H1_audio___15_30_00.lab
* Hive1_31_05_2018_NO_QueenBee_H1_audio___15_40_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___15_00_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___15_10_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___15_20_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___15_30_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___15_40_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___15_50_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___16_00_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___16_10_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___16_20_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___16_30_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___16_40_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___16_50_00.lab
* Hive3_12_07_2017_NO_QueenBee_H3_audio___17_00_00.lab
* Hive3_15_07_2017_NO_QueenBee_H3_audio___06_10_00.lab
* Hive3_15_07_2017_NO_QueenBee_H3_audio___06_20_00.lab
* Hive3_15_07_2017_NO_QueenBee_H3_audio___06_30_00.lab
* Hive3_15_07_2017_NO_QueenBee_H3_audio___06_40_00.lab
* Hive3_15_07_2017_NO_QueenBee_H3_audio___06_50_00.lab
* Hive3_15_07_2017_NO_QueenBee_H3_audio___07_00_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___06_10_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___06_20_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___06_30_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___06_40_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___06_50_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___07_00_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___15_00_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___15_10_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___15_20_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___15_30_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___15_40_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___15_50_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___16_00_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___16_10_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___16_20_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___16_30_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___16_40_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___16_50_00.lab
* Hive3_20_07_2017_QueenBee_H3_audio___17_00_00.lab

### Project Information
* README.md
* Term Project Final Report.pdf
* Zenodo documentation.pdf

### Metadata
* datacite_metadata.json
* datacite_metadata.xml
