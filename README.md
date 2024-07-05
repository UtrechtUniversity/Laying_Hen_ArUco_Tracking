# Laying_Hen_ArUco_Tracking
:movie_camera: :hatching_chick: :hatched_chick: :baby_chick: :chicken:

doi to be added

## Examining tracking of ArUco laying hen backpacks through comparison with manual annotation

https://github.com/UtrechtUniversity/Laying_Hen_ArUco_Tracking/assets/174421950/acabdf27-3d8e-4ec9-9d80-3479d2da15a0

## Background (abstract)
The demand for improved animal welfare has lead to technological developments to effectively monitor and evaluate animal welfare. Measuring behaviour as an indicator of welfare has potential, but tracking and identifying animals remains technically challenging. Computer-readable markers called ArUco markers provide a solution to track and identify individual animals in a group from a single data source (video). To examine the technical performance of this technology, we equipped pullets from two commercial laying hen hybrids housed in small groups with lightweight ArUco marker backpacks. The laminated paper backpacks with the printed marker on the middle of the back of the animals were tracked with top down view cameras. The fit of the backpacks differed between the layer hybrids, but for the hybrid with the most optimal fit, we were able to identify 94.0% of the individuals and track them 76.0% of the time they should be tracked. By applying a threshold on the minimum percentage of time tracked, ArUco position data could be used as a stand-alone application as well, for the ArUco data was comparable to the data from manually tracked pullets. For research and semi-commercial settings, ArUco markers could provide a powerful method to identify and track hens. 


## Available data:
- ArUco tracking data, stored csv files in folder /data/ArUco/
- Manually annotated bounding box data stored in txt files named starting with gt in folder /data/MOT/
- Overview file linking ArUco and bounding box files stored at /data/
- Pen edges per video stored in csv file at /data/

## Data not included - available on request:
- original videos
- videos with the plotted bounding boxes and ArUco tracking such as plotted above

## Overview of the scripts:
All code is written in Python :snake: for speed and to enable future upscale and deal with the current large data size. 


1. Part 1, 2 and 3 to combine, filter and clean all data into one data frame
2. Part 4 examine the quality of tracking in numbers
3. Pat 5 and 6 examine the quality of tracking visually


## Contact:
[Arjen van Putten](https://www.uu.nl/staff/AvanPutten) \
e-mail: a.vanputten1@uu.nl 

[Mona Giersberg ](https://www.uu.nl/staff/MFGiersberg) \
[Bas Rodenburg](https://www.uu.nl/staff/TBRodenburg
)


[Research group at Utrecht University - Animals in Science and Society](https://www.uu.nl/staff/organisationalchart/dgk/203/1036)

This paper contributes to one of the subprojects of the [IMAGEN](https://www.nwo.nl/onderzoeksprogrammas/perspectief/perspectief-toekenningen/animal-group-sensor-integrating-behavioural-dynamics-and-social-genetic-effects-to-improve-health-welfare-and-ecological-footprint-of-livestock-imagen) program 
