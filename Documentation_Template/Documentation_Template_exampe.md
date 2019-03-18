
This documentation file was generated on  2019-03-05 by Mark Landon


## GENERAL INFORMATION


1) Title of Dataset VIIRS Detected Fire Pixel in Indonesia 2012 thorough 2018 v2


2) Creator Information  

Name:  Mark Landon  
Institution:  Oregon State University  
College, School or Department:  Environment Sciences
Address:  Heckart Lodge  
2900 SW Jefferson Way  
Oregon State University  
Corvallis, OR 97331-2121  
Email:  landonma@oregonstate.edu  
ORCID:  0000-0002-0798-6621  
Role:  Primary Investigator  

Name:  Sam Smith   
Institution:  Oregon State University  
College, School or Department:  Environment Sciences
Address:  Heckart Lodge  
2900 SW Jefferson Way  
Oregon State University  
Corvallis, OR 97331-2121  
Email:  landonma@oregonstate.edu  
ORCID:  0000-0002-0798-3333  
Role:  Co-Investigator

3) Collaborator information

Name: Joe Collaborer  
Institution:   Oregon State University
College, School or Department:   Environment Sciences
Address:  Heckart Lodge  
2900 SW Jefferson Way  
Oregon State University  
Corvallis, OR 97331-2121  
Email:  landonma@oregonstate.edu  
ORCID:  0000-0002-0798-5555  
Role:  Data Analyst

4) Contact Information  

Name:  Mark Landon  
Institution:  Oregon State University  
College, School or Department:  
Address:  Heckart Lodge  
2900 SW Jefferson Way  
Oregon State University  
Corvallis, OR 97331-2121  
Email:  landonma@oregonstate.edu  
ORCID:  0000-0002-0798-6621  


## CONTEXTUAL INFORMATION


1) Abstract for the dataset  
The data set is a set of points where fires were detected using the VIIRS sensor. Each point represents an infrared anomaly and spans from 2012 to 2018. The data set is separated into several shape files. One contains all the fire points in regions within the Fire Free Villages. Another contains all the detected fire pixels in Indonesia for the time period.


2) Context of the research project that this dataset was collected for.  
The project was designed to asses the differences in the use of the slash-and-burn farming techniques on Indonesian Palm Oil farms in areas participating in APRIL's Fire Free Village Program(FFVP). The project looks at the clustering and number of fires in the treated group (those in the FFVP) compared to the untreated groups(all other areas).


3) Date of data collection:  
2012-01-01 to 2018-12-31

4) Geographic location of data collection:  
Indonesia,
Latitude North 5.47982086834, Latitude South -10.3599874813, Longitude West 95.2930261576, Longitude East 141.03385176

5) Funding sources that supported the collection of the data:  
This work was supported by  the National Science Foundation under grant No 1234567.




## SHARING/ACCESS INFORMATION



1) Licenses/restrictions placed on the data:  
This work is licensed under a Creative Commons No Rights Reserved (CC0) license

2) Links to publications related to the dataset:  
*[If there is a publication that uses or cites the data that has not been approved yet, include it here anyway, with as much information as you have at the moment (e.g. authors and title). If the publications have been published include the DOI in the citation. ]*

3) Links to other publicly accessible locations of the data:
None

4) Recommended citation for the data:  
Landon, M. & Smith, S. (2019) VIIRS Detected Fire Pixel in Indonesia 2012 thorough 2018 v2[Data set.] Oregon State University. https://doi.org/10.7267/123456DOI ]


5) Dataset Digital Object Identifier (DOI)  
10.7267/123456DOI

## VERSIONING AND PROVENANCE


1) Last modification date  
2019-03-05


2) Links/relationships to other versions of this dataset:  
https://doi.org/10.7267/678910DOI
This is an updated version of the 2016 dataset. !!This version included two additional years of the VIIRS satellite data as well as three additional village which have been added to the Fire Free Village program.

3) Was data derived from another source?  
This data was derived from VIIRS satellite data !! more informaion and link, !! shape file of 



4) Additional related data collected that was not included in the current data package:



## METHODOLOGICAL INFORMATION

1) Description of methods used for collection/generation of data:  
The Visible Infrared Imaging Radiometer Suite (VIIRS) is an active fire product and is part of the Fire Imformation for Resource Managment Sytem (FIRMS). This sensor is aboard the joint NASA/NOAA Suomi National Polar-orbiting Partnership (Suomi-NPP) satellite. The sensor looks for strong emissions in the mid-infrared bands. A suite of tests then filter out cloud mask and other false alarms. The algorithm and full description can be [read here](https://cdn.earthdata.nasa.gov/conduit/upload/4681/Schroeder_et_al_2014b_RSE.pdf).!! change name and decib of link

2) Methods for processing the data:  
The data was first process in ArcGIS Pro v2.3.1 then process in RStudio Desktop 1.1.463 with R-3.5.2. Using the select tool all observations with a low confidence were filtered out only leaving the observations with nominal or high confidence. The identity tool was then used to add the region, sub-district and village name to the points. The select tool was used to separate the points with the following DESA names from the rest of the data: Sering, Pelalawan, Kuala Tolam, Teluk Meranti, Teluk Binjai, Petodaan, Kuala Panduk, Pulau Muda, Langgam, Penarikan, Pkl Gondai, Tanjung Padang, Lukit and Olak. The selected points were then make into a new shape file. !! R scribe


3) People involved with sample collection, processing, analysis and/or submission:  
The data processing which created the modified shape files was done by Mike Wazowski.


## DATA & FILE OVERVIEW

1) File List  

      A. Filename: VIIRS_12_18_INDONESIA.shp
        Short description: VIIRS fire pixels for Indonesia 2012 to 2018

      B. Filename: VIIRS_12_18_TREATED.shp
        Short description: VIIRS fire pixels for Indonesia 2012 to 2018



2) Relationship between files:
VIIRS_12_18_TREATED.shp is a subset of VIIRS_12_18_INDONESIA.shp contain only those in .

3) Formats  
Both files are a shape file (.shp). There are several parts to a shape file but you open them in GIS software you can naviagate to the .shp.

!! talk about other file names

## TABULAR DATA-SPECIFIC INFORMATION FOR: VIIRS_12_18_INDONESIA.shp


1) Number of variables: 28 variables


2) Number of cases/rows: 2,304,511



3) Missing data codes:
        -9999   This is the number used for observations that were not recorded


4) Variable List  

1) Name: OBJECTID  
 Description: A unique ID for each row  

2) Name: LATITUDE  
 Description: The latitudinal center of nominal 375 m fire pixel  

3) Name: LONGITUDE  
 Description:  The longitudinal center of nominal 375 m fire pixel  

4) Name: BRIGHT_ti4  
 Description: VIIRS 1-4 brightness temperature(Kelvin) of the fire pixel  

5) Name: SCAN  
 Description: Actual along scan pixel size, 375 m at nadir  

6) Name: TRACK  
 Description: Actual along track pixel size, 375 at nadir   

7) Name: ACQ_DATE  
 Description: The date that the observation was recorded ( Month/Day/Year, Time (AM/PM) )   

8) Name: ACQ_TIME  
 Description: The time the observation was recorded in (HHMM)  

9) Name: Satellite  
  Satellite that recorded the fire pixel, N = Suomi National Polar-orbiting Partnership (Suomi-NPP)  


9) Name: CONFIDENCE  
 Description: The confidence that the observation was a fire. l = low confidence, n = nominal, h = high confidence  

10) Name: VERSION  
 Description:  VIIRS algorithm version

11) Name: BRIGHT_ti5  
 Description: I-5 Channel brightness temperature (Kelvin) of the fire pixel  

12) Name: FRP  
 Description: Fire radiative power (MW)!!  

 24) Name: DAYNIGHT  
  Description: D= Daytime fire, N= Nighttime fire  

24) Name: DESA  
 Description:  Name of the village where the observation was detected

25) Name: KECAMATAN  
 Description: Name of the province where the observation was detected  

26) Name: KABUPATEN  
 Description: Name of the sub-district where the observation was detected  

27) Name: PROPINSI  
 Description:  Name of the district where the observation was detected

28) Name: LUAS  
 Description: Whether or not the point was on Sumatra or not (0 or 1)

## TABULAR DATA-SPECIFIC INFORMATION FOR: VIIRS_12_18_TREATED.shp


 1) Number of variables: 28 variables


 2) Number of cases/rows: 45,432



 3) Missing data codes:
         -9999   This is the number used for observations that were not recorded


 4) Variable List  


    Name: Species  
    Description: Species of the Drosophila sampled  
    DML = Drosophila melanogaster  
    DMJ = Drosophila mojavensis  
    O = Other  

    A. Name: *[variable name]*  
    Description: *[description of the variable]*  

    B. Name: *[variable name]*  
    Description: *[description of the variable]*  
                *[Value labels if appropriate. Units if appropriate.]*   
 1) Name: OBJECTID  
  Description: A unique ID for each row  

 2) Name: LATITUDE  
  Description: The latitudinal center of nominal 375 m fire pixel  

 3) Name: LONGITUDE  
  Description:  The longitudinal center of nominal 375 m fire pixel  

 4) Name: BRIGHT_ti4  
  Description: VIIRS 1-4 brightness temperature(Kelvin) of the fire pixel  

 5) Name: SCAN  
  Description: Actual along scan pixel size, 375 m at nadir  

 6) Name: TRACK  
  Description: Actual along track pixel size, 375 at nadir   

 7) Name: ACQ_DATE  
  Description: The date that the observation was recorded ( Month/Day/Year, Time (AM/PM) )   

 8) Name: ACQ_TIME  
  Description: The time the observation was recorded in (HHMM)  

 9) Name: Satellite  
   Satellite that recorded the fire pixel, N = Suomi National Polar-orbiting Partnership (Suomi-NPP)  


 9) Name: CONFIDENCE  
  Description: The confidence that the observation was a fire. l = low confidence, n = nominal, h = high confidence  

 10) Name: VERSION  
  Description:  VIIRS algorithm version

 11) Name: BRIGHT_ti5  
  Description: I-5 Channel brightness temperature (Kelvin) of the fire pixel  

 12) Name: FRP  
  Description: Fire radiative power (MW)!!  

  24) Name: DAYNIGHT  
   Description: D= Daytime fire, N= Nighttime fire  

 24) Name: DESA  
  Description:  Name of the village where the observation was detected

 25) Name: KECAMATAN  
  Description: Name of the province where the observation was detected  

 26) Name: KABUPATEN  
  Description: Name of the sub-district where the observation was detected  

 27) Name: PROPINSI  
  Description:  Name of the district where the observation was detected

 28) Name: LUAS  
  Description: Whether or not the point was on Sumatra or not (0 or 1)  
  
  !! add r and code specifc section and packages 
  rcode in github repo and will be kept updated
!! make sure csv gis

!! description of r variables under usage or other in code sp

!!FGDC CSDGM talk about in methodalogy
