# MB-System OCEANS26 Tutorial
# OCEANS 2026 Conference in Monterey, California, United States 
# September 21, 2026. 

This is a half-day tutorial on the “nuts and bolts” of using the MB-System software package for processing multibeam sonar data collected on Autonomous Underwater Vehicles (AUVs). 

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

The MB-System website is at:
	https://www.mbari.org/technology/mb-system/

You may also want to check out MB-System's extensive tutorial, including YouTube videos, available at GitHub  
	https://github.com/dwcaress/MB-System-Tutorial/ (description at https://www.mbari.org/technology/mb-system/tutorials/ )

Note that installation of MB-System is not a focus of this tutorial. Please see the instructions at 
	https://www.mbari.org/technology/mb-system/installation/ 
	
For assistance and advice you can join the MB-System User Discussion List 
	https://www.mbari.org/technology/mb-system/discussion/ for assistance. 

**Bring your laptop with MB-System installed, if possible, and bring a 3-button mouse. We will have two spare computers available with MB-System installed for those without MB-System on their own computer to share.**

Google Drive links to sample datasets:

   MBARI Mapping AUV: https://drive.google.com/file/d/1CDTsTMylS65rSRw-CFSSERe5OI6uDhV4/view?usp=share_link

   SOI Hugin AUV The Childlike Empress: [https://drive.google.com/file/d/1CDTsTMylS65rSRw-CFSSERe5OI6uDhV4/view?usp=share_link](https://drive.google.com/file/d/1C2nRKUOSCnvYjAXJ3ZqBYVTDAlEtQWH6/view?usp=share_link)

   WHOI AUV Sentry: https://drive.google.com/file/d/1-CJXv0o50TdJhlDW5lKZfWQa2Vfuh-rL/view?usp=share_link
Presenters:

- [Jennifer Paduan](https://www.mbari.org/person/jennifer-b-paduan/), Senior Research Specialist, [Seafloor Mapping Team](https://www.mbari.org/technology/seafloor-mapping/), MBARI

- [Eve Lundsten](https://www.mbari.org/person/eve-lundsten/), Research Specialist, [Continental Margin Processes Team](https://www.mbari.org/team/continental-margin-processes/), MBARI

- [David Caress](https://www.mbari.org/person/dave-caress/), Principle Engineer, [Seafloor Mapping Team](https://www.mbari.org/technology/seafloor-mapping/), MBARI


 <img width="432" height="243" alt="image" src="https://github.com/user-attachments/assets/666097cd-d61f-431e-8334-1b0954df6df6" />


Overview PowerPoint slide with topics covered in the workshop and screen grabs of user interfaces from three of the MB-System programs used regularly for AUV bathymetry data processing, each of which will be explored. 


