*[Instructions in this document are in between brackets.]*  
*[Dates in this document should use the format YYYY-MM-DD.]*  
*[Scholarly outputs cited in this document should follow a consistent style (e.g. APA style)]*  
*[When you are done filling this template delete all instructions and delete any sections or questions that do not apply to your dataset.]*  
*[All of the items in this template are optional, but fill it as thoroughly as possible to ensure the reusability of your dataset.]*  
*[You may create more than one readme file in your dataset, if appropriate (e.g. one for your tabular data, one for your code)]*  
*[This template was created by Research Data Services at Oregon State University by modifying and expanding the University of Minnesota Libraries readme template that can be found in z.umn.edu/readme]*  
*[Other sources used to elaborate this dataset: Georgia tech metadata template http://d7)library.gatech.edu/research-data/metadata;]*  
*[For questions or guidance about using this template contact researchdataservices@oregonstate.edu]*  
*[This template is published under a CC0 license. You are free to reuse, redistribute and modify this template as you wish.]*  

This documentation file was generated on *[date in YYYY-MM-DD format]* by *[Name]*


## GENERAL INFORMATION


1) Title of Dataset


2) Creator Information  

Name:  Mark Landon  
Institution:  Oregon State University  
College, School or Department:  
Address:  Heckart Lodge  
2900 SW Jefferson Way  
Oregon State University  
Corvallis, OR 97331-2121  
Email:  landonma@oregonstate.edu  
ORCID:  0000-0002-0798-6621  
Role:  Primary Investigator  

Name:  Mark Landon  
Institution:  Oregon State University  
College, School or Department:  
Address:  Heckart Lodge  
2900 SW Jefferson Way  
Oregon State University  
Corvallis, OR 97331-2121  
Email:  landonma@oregonstate.edu  
ORCID:  0000-0002-0798-6621  
Role:  Primary Investigator  

3) Collaborator information
*[Collaborators are not authors, but have contributed somehow to the dataset.]*

Name: Joe Collaborer  
Institution:  
College, School or Department:  
Address:  
Email:  
ORCID:  
Role:  

4) Contact Information  
*[Usually a creator, but may be somebody else. Consider adding more than one contact if the main contact is expected to change positions soon (e.g. a student expected to graduate)]*

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
The data set is a set of points where fires were detected using the VIIRS sensor. Each point represents an infrared anomaly and spans from 2012 to 2018. The data set is separated into several shape files. One contains all the fire points in regions within the Fire Free Villages. Another contains all the fire points not in the regions participating in the Fire Free Village Program. Another contains only the fire points not in the regions participating in the Fire Free Village Program on the Island of !!.


2) Context of the research project that this dataset was collected for.  
The project was designed to asses the differences in the use of the slash-and-burn farming techniques on Indonesian Palm Oil farms in areas participating in APRIL's Fire Free Village Program(FFVP). The project looks at the cluster and number of fires in the treated group (those in the FFVP) compared to the untreated groups(all other areas).


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


4) Recommended citation for the data:  
Landon, M. & Smith, J. (2018) Title of this wonderful dataset [Data set. Oregon State University. https://doi.org/10.7267/123456DOI ]


5) Dataset Digital Object Identifier (DOI)  
10.7267/123456DOI

## VERSIONING AND PROVENANCE


1) Last modification date  
2019-02-26


2) Links/relationships to other versions of this dataset:  
*[If there are previous versions explain where the other version is, when it was updated, and summarize the changes.]*  
*[If a very granular description of the versions of the dataset is needed (e.g. file by file) this section can be moved to Data and File overview.]*


3) Was data derived from another source?  
Yes
The
*[If there is code in the dataset, and the code is in a repository explain how this snapshot of the code is tagged in the repository]*


4) Additional related data collected that was not included in the current data package:



## METHODOLOGICAL INFORMATION


*[Describe the methodology used to generate the dataset]*  
*[Include links or references to publications or other documentation containing methodological information]*  
*[Do not copy paste the methods section from a pending publication unless you have made sure that you can do that. Some journals may consider this as a publication, and will not accept a manuscript with a section that has already been published.]*  
*[If you want to refer to an article that has not been accepted for publication yet, include as much information as you have at the moment (e.g. authors and title). If the publication has been published include the DOI in the citation. If the publication does not have a DOI (like a dissertation) include a URL.]*



1) Description of methods used for collection/generation of data:  
*[experimental design or protocols used in data collection]*

2) Methods for processing the data:  
The data was first process in ArcGIS Pro v2.3.1 then process in RStudio Desktop 1.1.463 with R-3.5.2. The shape file containing the fire points and the shape file containing the region polygons. Using the select tool all observations with a low confidence were filtered out only leaving the observations with nominal or high confidence. The identity tool was then used to add the region, sub-district and village name to the points. The select tool was used to separate the points with the following names from the rest of the data: !!. The selected points were then make into a new shape file and removed from the orignal shape file. The orginal was process !!.

looked at the overview for Dates
took out the 2015 fires which caused the program to form


3) Instrument- or software-specific information needed to interpret the data:  
The shape files are viable in GIS software such as ArcGIS Pro or QGIS. The files were create using ArcGIS Pro v2.3.1.

5) Environmental/experimental conditions:  
*[e.g., cloud cover, atmospheric influences, computational environment, etc.]*


6) Describe any quality-assurance procedures performed on the data:


7) People involved with sample collection, processing, analysis and/or submission:  
Mike Wazowski did the data processing which created the modified shape files.



## DATA & FILE OVERVIEW


*[All files in the dataset should be listed here. If a file naming schema is used, it is fine to explain it instead of listing all the files. Include directory structure if necessary.]*  
*[Filenames should include extension.]*


1) File List  

      A. Filename:
        Short description:

      B. Filename:
        Short description:

      C. Filename:
        Short description:


2) Relationship between files:


3) Formats  
*[List all the formats present in this dataset. Include explanations or instructions if necessary (e.g. links to page describing a metadata standard)]*



## TABULAR DATA-SPECIFIC INFORMATION FOR: *[FILENAME]*



*[This section should be created for each file or dataset that requires explanation of variables. Typically, this is always needed for tabular data with columns and column headers. All variables should be described. Include the units.]*


1) Number of variables: 19 variables


2) Number of cases/rows:



3) Missing data codes:
        -9999   This is the number used for observations that were not recorded


4) Variable List  
*[Include all information that is important: Value labels if appropriate. Units if appropriate. Min and Max values if appropriate. ]*  
*[Example:]*

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
 Description:  

11) Name: BRIGHT_ti5  
 Description: I-5 Channel brightness temperature (Kelvin) of the fire pixel  

12) Name: FRP  
 Description: Fire radiative power (MW)!!  

 24) Name: DAYNIGHT  
  Description: D= Daytime fire, N= Nighttime fire  

24) Name: DESA  
 Description:  

25) Name: KECAMATAN  
 Description: Name of the province where the observation was detected  

26) Name: KABUPATEN  
 Description: Name of the sub-district where the observation was detected  

27) Name: PROPINSI  
 Description:  Name of the district where the observation was detected

28) Name: LUAS  
 Description: Wheather or not the point was on Sumatra or not (0 or 1)  

29) Name: MI_PRINX  
 Description:  
