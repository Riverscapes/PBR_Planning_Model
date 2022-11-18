---
title: 4. Manual Delineations 
weight: 1
---
The following layers were manually delineated using the <a href="https://riverscapes.github.io/PBR_Planning_Model/2_project_tree.html#:~:text=within%20this%20branch.-,Height%20Above%20Nearest%20Drainage%20(HAND),-Hillshade"> HAND</a> raster as well as <a href="https://earth.google.com/web/@10.7574218,34.78259653,621a,19577829d,35y,0h,0t,0r/data=Ci4SLBIgOGQ2YmFjYjU2ZDIzMTFlOThiNTM2YjMzNGRiYmRhYTAiCGxheWVyc18w"> Google Imagery.</a> 

- Riparian Wetland Corridor 
- Off-Channel Rearing Habitat
- Forage Area




## Riparian Wetland Corridor 

The Riparian Wetland Corridor represents the lowest lying areas within the valley bottom that are most likely to be reconnected post-restoration. HAND is used to highlight these low-lying areas; this is done by extracting a 0.5 - 1m contour polygon from the raster itself. This gives us a baseline of what will likely be able to flood after restoration has occured. Google imagery is then used to manually refine the polygon by examining other lines of evidence such as oxbows, abandoned channels or areas of inundation that could be indicative of other low-lying areas that fall outside of the extracted contours.   

<img src="{{ site.baseurl }}/assets/images/RWC.PNG" width="450">

## Off-Channel Rearing Habitat  

The Off-Channel Rearing Habitat layer is an attempt to highlight secondary channels and depressions on the landscape (both connected and abondoned) that could serve as rearing habitat. Google Imagery is used to identify these areas within the RWC. 

<img src="{{ site.baseurl }}/assets/images/OCRH.PNG" width="450">


## Forage Area

The Forage Area layer represents grazing areas within the valley bottom, but outside of the Riparian Wetland Corridor that could benefit from restoration. This layer is produced by simply clipping away the RWC layer from the existing <a href="https://riverscapes.github.io/PBR_Planning_Model/2_project_tree.html#:~:text=its%20nested%20contents.-,Valley%20Bottom,-This%20branch%20contains">Valley Bottom layer</a>. 

<img src="{{ site.baseurl }}/assets/images/FA.PNG" width="450">

