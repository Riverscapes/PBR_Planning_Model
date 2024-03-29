---
title: 2. Project Tree
weight: 1
---

<img src="{{ site.baseurl }}/assets/images/tree.PNG" width="300"> 

Once the model is added to your preferred GIS, you should notice the Riverscapes toolbar or “Project Tree”. From here users can apply basemaps and access individual layers or <a href="https://riverscapes.github.io/PBR_Planning_Model/3_project_views.html"> project views.</a> Below are descriptions of each “branch” and its nested contents. 

## Valley Bottom 

This branch contains valley bottom outputs from the <a href="https://rcat.riverscapes.net/Documentation/Version_1.0/VBET.html"> Valley Bottom Extraction Tool (VBET).</a> 

- Valley Bottom (filled)
- Valley Bottom (hollow)

<img src="{{ site.baseurl }}/assets/images/VB.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/VB_leg.PNG" width="200">

## Current Riparian Condition 

This branch contains a classified vegetation map for the year 2000 as well as a Riparian Vegetation Departure (RVD) layer which is an output from the <a href="https://rcat.riverscapes.net/"> Riparian Condition Assessment Tool (RCAT).</a> 

- Existing Vegetation Map 

<img src="{{ site.baseurl }}/assets/images/VegMap2000.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/VegMap2000_leg.png" width="175">

- RCAT Riparian Vegetation Departure 

<img src="{{ site.baseurl }}/assets/images/RVD.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/RVD_leg.png" width="265">

## Pre-Treatment Process Space 

This branch contains an active channel layer or the "pre-restoration space". This is meant to give context on the current limitations of floodplain connectivity due to infrastructure. 

- Pre-Restoration Space (Active Channel)

<img src="{{ site.baseurl }}/assets/images/ActiveChannel.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/ActiveChannel_leg.png" width="280">

## Infrastructure Constrained Reaches 
This branch contains the Risk of Undesireable Dams layer from the <a href="https://brat.riverscapes.net/"> Beaver Restoration Assessment Tool (BRAT).</a> This layer highlights areas where LT-PBR may have negative effects on the surrounding infrasturcture. 

 - BRAT Risk of Undesirable Dams 

<img src="{{ site.baseurl }}/assets/images/Risk.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/Risk_leg.PNG" width="135">

## Restoration Space 

This branch houses three sub-folders: Capacity & Managment, Valley Bottom Fragmentation and Potential Post-Restoration Space. Each sub-folder contains layers that are intended to highlight areas within the watershed that have varying restoration potential. 

**Capacity & Managment:** This sub-folder houses the Existing Capacity layer which estimates the landscapes ability to support beaver dam building activity. The folder also contains the "Channel Spanning Structures Appropriate" layer which identifies the effort it would take to establish beaver dams and/or beaver dam analogs (BDAs) on the landscape. Both layers are BRAT outputs. 

   - BRAT Existing Capacity 

<img src="{{ site.baseurl }}/assets/images/ExistingCap.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/ExistingCap_leg.png" width="265">

   - Channel Spanning Structures Appropriate 

<img src="{{ site.baseurl }}/assets/images/StrucApprop.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/StrucApprop_leg.png" width="250">
    
**Valley Bottom Fragmentation:** This sub-folder contains an Infrastructure dataset along with an Accessible & Inaccessible layer which highlights areas of the valley bottom that have been disconnected due to infrastructure. **Note:** Inaccessible refers to the portion of the valley bottom that is cutoff from the river due to infrasturcture (leeves, elevated roadways,etc.) while Accessible refers to the portion of the valley bottom that could plausably flood but would require installation of instream structures. More information on how this layer is derived can be found <a href="https://rcat.riverscapes.net/Documentation/Version_2.0/RCAT/1-Preprocessing#:~:text=may%20be%20missing.-,Valley%20Bottom%20Preparation,-One%20of%20the"> here.</a>
 
   - Infrastructure

<img src="{{ site.baseurl }}/assets/images/Infrastructure.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/Infrastructure_leg.png" width="125">

   - Accessible & Inaccessible Valley Bottom
   - Accessible & Inaccessible Valley Bottom 500m (same layer, but segmented by 500m reaches)

<img src="{{ site.baseurl }}/assets/images/Accessible_VB.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/Accessible_VB_leg.png" width="150">
 
**Potential Post-Restoration Space:** This sub-folder houses <a href="https://riverscapes.github.io/PBR_Planning_Model/4_manual_delineations.html"> manually delineated layers </a> that represent the portions of the valley bottom that are most likey to be affected by infrastructure removal and installation of instream structures.

   - Off Channel Rearing Habitat - secondary channels adjacent to the Sprague 
   - River Wetland Corridor - lowest lying areas most likely to be reconnected after restoration 
   - Forage Area - grazing areas within the valley bottom that could benefit from restoration

<img src="{{ site.baseurl }}/assets/images/Post_Restore.PNG" width="450"><img src="{{ site.baseurl }}/assets/images/Post_Res_leg.PNG" width="220">

## Topography 

This branch houses the Height Above Nearest Drainage (HAND) and the hillshade raster. HAND rasters represent the vertical distance between a location and its nearest stream. See the <a href="https://riverscapes.github.io/PBR_Planning_Model/4_manual_delineations.html"> Manual Delineations</a> page for more information on how HAND is used to delineate low-lying areas within the watershed. 

  - Height Above Nearest Drainage (HAND)
  - Hillshade 

<img src="{{ site.baseurl }}/assets/images/HAND.PNG" width="450">

## Summary Statistics

From this branch you can access the Summary Statistics CSV. 

- <a href="{{ site.baseurl }}/assets/css/Sprague_SummaryStat.csv">PBR Summary Stats</a>
