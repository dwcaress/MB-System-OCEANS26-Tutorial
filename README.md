# MB-System-OCEANS26-Tutorial
This repository hosts files to be used during the MB-System tutorial presented at the OCEANS 2026 Conference in Monterey, California, United States on September 21, 2026. 

The MB-System workflows we use to process and display seafloor multibeam survey data will be discussed using scripts we have developed for three different Autonomous Underwater Vehicles (AUVs): an MBARI operated Dorado class AUV mapping with a Teledyne T-50 400 kHz sonar, the WHOI operated vehicle AUV _Sentry_, and the Schmidt Ocean Institute operated Hugin AUV _The Childlike Empress_ mapping with a Kongsberg EM2040 sonar. Some of the MB-System programs will be demonstrated and participants can practice during the class. Example data for the tutorial will include survey data and processing scripts for each of the three vehicles...please stay tuned; they will all be available for download here by about 01 September!

Presenters:

- Jenny Paduan, Senior Research Specialist, Seafloor Mapping Team, MBARI (https://www.mbari.org/team/seafloor-mapping/)

- Eve Lundsten, Research Specialist, MBARI, Continental Margin Processes Team (https://www.mbari.org/team/continental-margin-processes/)


You may also want to check out MB-System's extensive tutorial, including YouTube videos, available at GitHub here https://github.com/dwcaress/MB-System-Tutorial/ (description at https://www.mbari.org/technology/mb-system/tutorials/ )

Note that installation of MB-System is not a focus of this tutorial. Please see the instructions at https://www.mbari.org/technology/mb-system/installation/ and subscribe to the MB-System User Discussion List https://www.mbari.org/technology/mb-system/discussion/ for assistance. 

# Abstract
We propose to offer a half-day tutorial on the “nuts and bolts” of using the MB-System software package for processing multibeam sonar data collected on Autonomous Underwater Vehicles (AUVs). 

MB-System (https://www.mbari.org/technology/mb-system/) is open-source software developed by David Caress (MBARI), Christian dos Santos Ferreira (MARUM), and Dale Chayes (UNH CCOM, retired) for the processing and display of seafloor mapping data. MB-System development began in the early 1990’s with US National Science Foundation funding to support data collected by UNOLS and other oceanographic research vessels, and since 1998, has been funded by the Packard Foundation as part of MBARI development projects to support high resolution mapping from AUVs. Surveys from submerged platforms such as AUVs and ROVs involve additional challenges beyond conventional mapping, including designing complicated surveys in complex terrain, addressing interference from other acoustic sources on the vehicle, correcting for inertial navigation drift, and merging multiple surveys collected over time on terrain that has experienced changes, such as submarine canyons and active volcanoes. Other tasks for which we use MB-System routinely include assessing attitude sensor biases, applying tide corrections, and gridding and outputting data as products that can be useful in GIS. 

This tutorial will introduce MB-System to the participants and then walk them through how to: 
1.	Design AUV survey missions 
2.	Set up MB-System processing (the “pre-processing” stage) for 3 different AUV platforms
3.	Edit multibeam bathymetry data in both waterfall and 3-D point cloud views
4.	Estimate and correct for attitude biases
5.	Adjust vehicle navigation to match features in overlapping swathes
6.	Merge surveys
7.	Generate common data products, including GIS objects

These steps will be shown as sequences of screen grabs and videos in PowerPoint and by actively working on example datasets.  Templates of scripts we work with will be provided, and our work-flow and methods will be discussed, including of newer features of MB-System. 

This tutorial will focus on 1-meter-scale multibeam bathymetry and backscatter collected using MBARI’s Dorado Mapping AUVs (https://www.mbari.org/technology/seafloor-mapping-auv/), WHOI’s AUV Sentry (https://ndsf.whoi.edu/sentry/), and SOI’s Hugin Superior AUV (https://schmidtocean.org/advances-r-v-falkor-toos-mapping-capabilities/ ). Since MB-System supports a large number of data formats from most commonly used mapping sonars, these examples should be broadly relevant to users of other AUV or ship-mounted sonars. Participants who have experience with multibeam sonars, particularly on submerged platforms, will find this tutorial most beneficial. Novice users will come away with an introduction to MB-System and an appreciation for the complexities of working with AUV mapping data. This tutorial will NOT include installation or troubleshooting of MB-System working on participant’s computers. 

 <img width="432" height="243" alt="image" src="https://github.com/user-attachments/assets/666097cd-d61f-431e-8334-1b0954df6df6" />


Overview PowerPoint slide with topics covered in the workshop and screen grabs of user interfaces from three of the MB-System programs used regularly for AUV bathymetry data processing, each of which will be explored. 


