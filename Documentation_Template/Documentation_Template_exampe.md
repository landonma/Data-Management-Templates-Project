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
Institution:  !!
College, School or Department:  
Address:  !!
Email:  landonma@oregonstate.edu
ORCID:  0000-0002-0798-6621
Role:  Primary Investigator

3) Collaborator information
*[Collaborators are not authors, but have contributed somehow to the dataset.]*

Name:  
Institution:  
College, School or Department:  
Address:  
Email:  
ORCID:  
Role:  

Name:  
Institution:  
College, School or Department:  
Address:  
Email:  
ORCID:  
Role:  

4) Contact Information  
*[Usually a creator, but may be somebody else. Consider adding more than one contact if the main contact is expected to change positions soon (e.g. a student expected to graduate)]*

Name:  
Institution:  
College, School or Department:  
Address:  
Email:  
ORCID:  


## CONTEXTUAL INFORMATION


1) Abstract for the dataset  
The data set is a set of points containing fires



2) Context of the research project that this dataset was collected for.  
*[Any contextual information that will help to interpret the dataset. You can give details about the research questions that prompted the collection of this dataset. ]*


3) Date of data collection:  
2012-02-01 to 2019-02-01

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
*[Doe, J. & Smith, J. (2018) Title of this wonderful dataset *[Data set]*. Oregon State University. https://doi.org/10.7267/doid01DOI ]*


5) Dataset Digital Object Identifier (DOI)  
*[Information to add at the end of the submission process, after dataset review.]*


6) Limitations to reuse  
*[Describe any known problems or caveats that would limit reuse of the data.]*



## VERSIONING AND PROVENANCE


1) Last modification date  
2019-02-26


2) Links/relationships to other versions of this dataset:  
*[If there are previous versions explain where the other version is, when it was updated, and summarize the changes.]*  
*[If a very granular description of the versions of the dataset is needed (e.g. file by file) this section can be moved to Data and File overview.]*


3) Was data derived from another source?  
Yes
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
imported FIRMs  
imported shape file of the regions
Filtered out all the fires below 50% confidence
looked at the overview for Dates
took out the 2015 fires which caused the program to form


3) Instrument- or software-specific information needed to interpret the data:  
*[If software is needed to interpret the data, explain where to get the software. If software is not openly available include it in the dataset (if possible). If including the software is not possible consider changing the format of the dataset. Include version of software. ]*


4) Standards and calibration information, if appropriate:


5) Environmental/experimental conditions:  
*[e.g., cloud cover, atmospheric influences, computational environment, etc.]*


6) Describe any quality-assurance procedures performed on the data:


7) People involved with sample collection, processing, analysis and/or submission:  
*[If they are not include as collaborators, or if you want to describe more carefully who did what.]*



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


1) Number of variables: 46 variables


2) Number of cases/rows: 56,494 rows



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
 Description:  

3) Name: LONGITUDE  
 Description:  

4) Name: BRIGHTNESS  
 Description:  

5) Name: SCAN  
 Description:  

6) Name: TRACK  
 Description:  

7) Name: ACQ_DATE  
 Description: The date that the observation was recorded (Month/Day/Year, Time (AM/PM))   

8) Name: ACQ_TIME  
 Description: The time the observation was recorded in HHMM format  

9) Name: CONFIDENCE  
 Description: The cofidence that the observation was a fire (0-100%)  

10) Name: VERSION  
 Description:  

11) Name: BRIGHT_T31  
 Description:  

12) Name: FRP  
 Description: Fire radiative power (MW)  

13) Name: treecover  
 Description:  

14) Name: loss  
 Description:  

15) Name: lc_seasia  
 Description:  

16) Name: lc_ind  
 Description:  

17) Name: ifl  
 Description:  

18) Name: peat  
 Description: Whether or not the observation was detected on peatland (0 or 1)  

19) Name: legal  
 Description:  

20) Name: forma  
 Description:  

21) Name: primary_fo  
 Description:  

22) Name: ISO  
 Description:  

23) Name: ISLAND  
 Description: The name of the island where the observation was detected  

24) Name: TYPE  
 Description:  

25) Name: PROVINCE  
 Description: Name of the province where the observation was detected  

26) Name: SUBDISTRIC  
 Description: Name of the sub-district where the observation was detected  

27) Name: DISTRICT  
 Description:  Name of the district where the observation was detected

28) Name: sumatra  
 Description: Wheather or not the point was on Sumatra or not (0 or 1)  

29) Name: moratorium  
 Description:  

30) Name: primary_forest  
 Description:  

31) Name: NAME  
 Description:  

32) Name: ID  
 Description:  

33) Name: ID_KEC  
 Description:  

34) Name: ID_KAB  
 Description:  

35) Name: VILLName  
 Description:  

36) Name: pulpwood  
 Description:  

37) Name: palm_oil  
 Description:  

38) Name: logging  
 Description:  

39) Name: loggint  
 Description:  

40) Name: HIGH_CONF  
 Description:  

41) Name: cert_scheme  
 Description:  

42) Name: CERT_SCHEM  
 Description:  

43) Name: treecover_pct  
 Description:  

44) Name: lc_global  
 Description:  

45) Name: SATELLITE  
 Description:  

46) Name: wdpa  
 Description:  
