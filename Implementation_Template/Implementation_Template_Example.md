# Health and Value of the Brian Booth Wetlands Data Implementation Plan
*[REMINDER: This is not a Data Management Plan template. This is a Data Management Plan Implementation template. To learn more about the difference between the two and to find templates to write a data management plan for a grant proposal see our [FAQ](https://landonma.github.io/Data-Management-Templates-Project/faq.html) ]*
Table of Contents  
[Data Management Implementation Plan](#data-management-implementation-plan)  
[Data Management Units](#data-management-units)  
[Data Collection](#data-collection)  
[Data Documentation](#data-documentation)  
[Quality Control](#quality-control)  
[File Organization](#file-organization)  
[Formats](#formats)  
[Storage](#storage)  
[Backup](#backup)  
[Workflow Internal Data Sharing](#workflow-internal-data-sharing)  
[Data Use](#data-use)  
[Protection for Sensitive and Confidential Data](#protection-for-sensitive-and-confidential-data)  
[Management of Physical Samples](#management-of-physical-samples)  
[Data Publication](#data-publication)  
[Data Archival](#data-archival)  
[Roles and Responsibilities](#roles-and-responsibilities)  

## Data Management Implementation Plan


The data management plan approved by the NSA can be found at the followin location: !!R Locatioon!!
Contracts between OSU and the Oregon Parks department that involve data management can be found in !!R Location!! 
The data management plan that was submitted with the grant proposal for this project can be found in *[blank]* 
All data contain unrestricted (based on the [OSU's Data Classifications](https://uit.oregonstate.edu/ois/data-management-and-classification-overview) data except the raw data from the Wetlands Survey subproject which contains senitive information.
The IRB approvla for the Wetlands Survey subproject can be found here: !!R locatoin!!  

##### 1) Health and Value of the Brian Booth Wetlands


##### 2) Data Management Plan (DMP)
The data management plan for the project can be found in the shared R drive at "R:\projects\BrBoMaster\DMPMaster\DMP_latest.doc".  

##### 3) Data Description
The aim of the project is use a wide range of disciplines to look at function and health of the Brian Booth Wetlands which lies along the Central Oregon Coast. To do this, twelve people from five departments and one government agency will collect five datasets looking at different aspects of the same area. The datasets are as follow:

1. Meteorological data  
    - Readings from a station set up for the duration of the project (temperature, wind speed, humidity, ect)
2. Birds Census   
   - Spreadsheets with counts of migratory birds
   - Photographs and videos with geo-location tags
3. Water quality
   - instrumentation (dissolved oxygen, pH, turbidity, temperature, nutrients, etc)
   - lab data: phytoplankton and zooplankton species identification
   - spreadsheet, physical samples, photos and microscope images
4. Use of the wetlands as a recreational site
   - Interviews of visitors on how they use the wetlands and its value
5. Maps
   - Maps of the area that provide context for the project


## Data Management Plan and Documentation

##### Rationale and resources
##### Boiler plate text
##### Examples


## Data Management Units

Five groups of datasets will be generated during the course of this project.

1. Meteorological Group
	Type of dataset: Observational  
	Collection strategy: WxPRO weather station positioned near the center of the research site  
	Amount of data expected: 200 days of atmospheric data  

2. Bird Survey Group
	Type of dataset: observational  
	Collection strategy: Bird Survey conducted around 17 sites by 2 people visiting each site twice   
	Amount of data expected: 34 csv tables     

3. Water Quality Group
  Type of dataset: observational  
	Collection strategy: Water samples collected at 8 sites by 2 people during mid-March then analyzed in the lab
  Amount of data expected: 64 csv tables    

4. Wetlands Survey Group  
  Type of dataset: observational  
  Collection strategy: In person survey questionnaires conducted at the park  
  Amount of data expected: 30 questions survey from 50 participants  

5. Area Map Group  
  Type of dataset: observational
  Collection strategy: USGS Downloads  
  Amount of data expected: One geodatabase with 10 to 15 shape files  


## Data Collection

**Sampling sites:** *[Include information with description of sampling sites including important data about them such as location, official names to be referred to, instrumentation in each sampling site, etc. ]*  

Sample Site 1 (S01): 44.5136362,-124.06405418  
Sample Site 2 (SO2): 44.5174566,-124.07603136  
Sample Site 3 (S03): 44.51816278,-124.06811056  
Sample Site 4 (S04): 44.51735171,-124.07620103  
Sample Site 5 (S05): 44.51255573,-124.06886986  
Sample Site 6 (S06): 44.51908749,-124.06103387  
Sample Site 7 (S07): 44.51396917,-124.07317921  
Sample Site 8 (S08): 44.51666834,-124.07224023  
Sample Site 9 (S09): 44.51956984,-124.07594364  
Sample Site 10 (S10): 44.5167515,-124.07025754  
Sample Site 11 (S11): 44.52185365,-124.07368357  
Sample Site 12 (S12): 44.51717156,-124.06782326  
Sample Site 13 (S13): 44.51678279-124.08165506  
Sample Site 14 (S14): 44.51266873,-124.07660136  
Sample Site 15 (S15): 44.52547621,-124.07627525  
Sample Site 16 (S16): 44.52180154,-124.08229632  
Sample Site 17 (S17): 44.51773927,-124.06282085  

**Existing protocols:** *[Include the location of protocols relevant to the research that already exist, like lab safety protocols, sampling protocols, instrument installation protocols, etc. Include here all the contextual information relevant for the use of the protocol that is not explained in the protocol itself ]*  

Meteorological Group:
1. Name: Weather Station Setup, Maintenance and Extraction
2. Location: R:\projects\BrBoMaster\Metero\
3. Expected use: Marth Marien and anyone who assists her  
4. Training: Marth Marien will handle training  

Water Quality Group (1):  
1. Name: Water Sample Extraction  
2. Location: R:\projects\BrBoMaster\WaterQ\Documents  
3. Expected use: Cathy Thompson and Barbra Hubble   
4. Training: Shauna Thompson, the lab manager will handle training    

Water Quality Group (2):
1. Name: Water Sample Analysis  
2. Location: R:\projects\BrBoMaster\WaterQ\Documents  
3. Expected use: Kathy Thomas and Patrick Pullman   
4. Training: Shauna Thompson, the lab manager will handle training

Wetlands Survey Group:
1. Name: Questionnaire Survey Protocol  
2. Location: R:\projects\BrBoMaster\ !!  
3. Expected use: Barbara Hubble    

**New protocols:** *[For projects that involve the creation of routinely creating new protocols, describe the process of creating new protocols.]*  

Bird Survey Group:
1.  Process Modified Breeding Bird Survey  
2. Approval: Sam Singer will approve the protocol  
3. Tools *[If special tools will be used to create the protocol, specify]*  
4. Storage  R:\projects\BrBoMaster\Birds  
5. Update *[How to update the protocol]*  
6. Expected use Sam Singer and Arthur Chapman will use a breeding bird survey adjusted for smaller areas  

**Instrumentation:** *[Include relevant information about the instruments that will be used to collect data, like where to find instructions, maintenance to ensure that the sensors will work correctly, etc.]*  

**Software:** *[Include relevant information about the software that will be used to generate data. Where to access the documentation. Intellectual property information about the software to be aware of. ]*  

## Data Documentation
###### *Instructions*  
*[Describe how data will be documented throughout the project]*

###### *Text*  
Data will be documented throughout the research process using the following tools:

**Lab notebooks:**

Details about experiments and work in a lab are quickly forgotten unless they are written down. Be diligent in writing information into notebooks. Follow best practices:  
- Lab notebooks will always be bound notebooks. Blank notebooks can be found in *[blank]*. Number and date the notebook when you begin with a new one.  
-	Pages should always be numbered.
-	Write legibly and in a language understood by everybody in the lab.
-	Error correction: incorrect information should be visible, but clearly marked as incorrect.  Date, sign and explain the correction. Do not erase entries or blot them out.
-	Printed documentation added to the lab notebook should be attached permanently.
-	Note where all electronic files associated with the experiment are located.
-	All entries should be consecutive. Always record dates.
-	Backup: at the end of the day *[blank]* [scan, photograph…] the pages of the notebook that you worked on, and store them in *[blank]*

**Templates:** survey,   

**Readme:** *[If the project will be documented using readme files, include expectations about where they will be created, and which information will be recorded in them.]*  

##### Rationale and resources



## Quality Control
###### *Instructions*    
*[Most data need to go through a quality control process. Describe the process here, and describe how it will be documented. For ideas around defining levels of quality control, see the Guidance Document.]*
##### Rationale and resources
It may be useful to design different levels of quality control. For example:

**Level zero (L0):** Data as it is downloaded directly from an instrument or model. This data is often in binary format, impossible to understand or look at by a human unless it is processed by a program. These programs tend to be proprietary and they may or may not perform operations on the data. This data level may not exist. For example: binary files coming from a temperature sensor permanently installed in a stream.  

**Level one (L1):** Raw data in a format that is understandable by a human. There have been no corrections on these data. For example, a csv file obtained after running the programs supplied by the company that manufactured the instrument.  

**Level two (L2):** Verified data that have undergone quality control, including but not limited to:
*	Detecting sensor malfunctioning
*	Assessment of outliers
*	Calibration
*	Corrections for sensor drift or offset, data artifacts, etc.

Level two data are the best data that a researcher could use. Level two data should not include data that have undergone quality control procedures that are subjective to the researcher. When quality control is not necessary, L1 and L2 data may be the same.  

**Level three (L3):** L2 data that have been analyzed to answer specific research questions. Typically, this is the data that will be used to create figures in a publication. For example, if a principal component analysis was used to analyze three years of temperature data and published in a figure as part of a peer-reviewed article.  




## File Organization

###### *Instructions*    
*[Details about the organization of data files in shared or privatefolders. What name to give to  folders? What kind of filesshould be savedin each folder?Design file naming techniques so that file names are informative for all files, and consistent throughout the folders, regardless of the person creating the file.]*

Lab material must be connectable to their context in the real world (lab notebook, instrument settings, etc.). Proper lab data management will ensure this is possible.

- The directory containing experimental output should have the following format:
YYYY-MM-DD_notebook-page_descriptive-name
- The raw experimental data should be exported into an appropriate non-proprietary, long-term file format.
- Each directory should have a clearly labeled summary file (image, text file/document, or graph). The summary file should be printed out and placed in the lab notebook.



## Formats
###### *Instructions*    
*[Describe preferred formatsto save information and data. Describe situations in which files should be changed from one format to a different one.See the guidance document for a list of preferred formats for long term preservation.]*

##### Rationale and resources

Formats that will be better at long term preservation are formats that are platform independent (can be accessed from Linux, Mac and Windows), in an open format (no proprietary formats), and character based (not in binary format). There can be exceptions to all of these for the right reasons. For example, some data standards that are widely used in some disciplines, like netCDFs, save data in binary format.  
See [eCommons: Cornell's Digital Repository. Recommended file formats](http://guides.library.cornell.edu/ecommons/formats) for a table with existing formats for different types of content, and their probability for full term preservation.



## Storage  



## Backup



## Workflow Internal Data Sharing
Rationale: setting expectations about how and when datasets will be shared internally will minimize conflict during the project.


- The meteorological dataset will be made available to everyone involved with the project on the shared drive at the following location; R:\projects\BrBoMaster\Metero\. The data will be available in csv format accompanied by XML documents which adhere to EML metadata standards. Datasets will be consistently updated and calibrated throughout the project by Martha Marien. As datasets are updated, no notification will be given. Raw data will only be uploaded if there are no processed version and otherwise can be requested by emailing Martha Marien.


- The bird survey dataset will be made available to everyone involved with the project on the shared drive at the following location; R:\projects\BrBoMaster\Birds. The dataset will be available in CSV format accompanied by text files which include the metadata. Datasets will be uploaded within two weeks of data collection by the individual who collected it.. The first survey will be conducted in March and the second in May. Email notifications will be sent when the new datasets are uploaded. !!Level 2 !!


- The water quality datasets will be made available to everyone involved with the project on the shared drive at the following location; R:\projects\BrBoMaster\WaterQ. !! water quality data format !! Datasets will



## Data Use



## Protection for Sensitive and Confidential Data



## Management of Physical Samples



## Data Publication

##### Acknowledgment of Data Use

All members of the Project involved in roles related to data management will be acknowledged in some way. Specifically:

Members of the Project that were involved in data generation will be offered co-authorship to papers that make use of their data. This offer is required for any publications with data that is formally unpublished. After the first publication of a dataset this convention is not mandatory but is highly encouraged for the two years following the project's completion. Co-authorship will require participation in the interpretation of the data, writing, or critical review of the manuscript, approval of the final manuscript. The offer for co-authorship may be accepted or declined. When students (PhD or masters) accept co-authorship, the initiators of the article will commit to provide support and mentorship to the student, so that their role can be meaningful.

Datasets will be published separately from the research in a repository on OSU's Scholars Archive. Members of the Project with a significant data management contribution will be listed as co-authors in the data publication. Every member of the Project that makes use of the published datasets will cite the dataset and list it in the reference list in their publications.

When possible, publications will be made in journals that use the CRediT authorship taxonomy (http://docs.casrai.org/CRediT) or similar. The roles of each of the members of the Project involved in data management will be documented using the appropriate roles. Members of the Project involved in data analysis will be acknowledged in the acknowledgment section in papers and publications. 󠄀

## Data Archival



## Roles and Responsibilities
Rationale: Data management takes time and effort. In order to not oversee any important data management action, it should be clear to all the members of the team who is responsible for each of them.


#### Role definitions:  
**Principal Investigator (PI):** as designated by the funder. If there is no funder or the funder does not designate the principal investigator, it will be a faculty member.  
Bethany Barnard is the PI and will coordinate with all of the separate parts.

**Faculty Investigator:**
Three OSU faculty members are assigned to three of the subprojects:  
Rogers, Rick is responsible for the Meteorological Data  
Singer, Sam is responsible for the Birds Census  
Williams, Wallace is responsible for the Water Quality Data  

Dunning, Diane is Parks and Recreation Department employee and is responsible for the Wetland Interviews dataset.

**Team member:**  
Martha Marien is a technicians in the College of Earth, Ocean, and Atmospheric Sciences at OSU and will work on the meteorological dataset. Patrick Pullman is a Postdoc in the Department of Fisheries and Wildlife at OSU and will work on the bird survey dataset.  

**Student:**  
Five Oregon State University Students will be working on various projects. Arthur Chapman will work on the bird census. Cathy Thompson will work on the water quality data. Barbra Hubble and Henry Cortez will work on the wetlands survey. Julie Reynolds will work on the creation of the maps of the area.

#### Responsibilities
The responsibility below will be broken down by subproject.

 Rogers, Rick is responsible for the Meteorological Data  
 Singer, Sam is responsible for the Birds Census  
 Williams, Wallace is responsible for the Water Quality Data  
 Dunning, Diane is responsible for the Wetland Interviews  
 Bethany Barnard is responsible for the Maps dataset  

**DMP Implementation:** responsible for ensuring Data Management Plan and the Internal Data Sharing Plan move from planning into implementation; ensure that any practices, responsibilities, policies outlined in the plan are followed; ensure that new members of the Project will receive data management training; responsible for maintaining the Data Management Plan and the Internal Data Sharing Plan up to date, and making sure that all members of the Project understand and are prepared to apply the changes.  
*Responsible Parties:* Bethany Barnard will make sure all the subprojects are coming together and abiding by the DMP  
!! Make some changes in definitions, change the below to emphases the PII data, give access to new members  
**Access control:** responsible for regulating access to data based on the roles of the authorized user, whether from the project or not. Access is the ability to perform a specific task, such as view, create, or modify a file. Responsible for granting access to data by members outside of the project when requested during the duration of the project.  
*Responsible Parties:* Rick Rogers will control access to the meteorological dataset, Sam Singer will control access to the bird survey, Wallace Williams will control access to the water quality dataset, and Diane Dunning will control access to the wetland interviews, Bethany Barnard will control access to the maps.  

**Protection of sensitive and protected data:** responsible for complying with applicable laws and regulations, institutional policies, and ethical principles governing the conduct of human subjects research, sensitive and protected data.  
*Responsible Parties:* Diane Dunning will protect the identifiable version of the wetlands survey dataset. The OSU IRB approved protocols are listed in the R drive in the admin folder. Questions about these protocols or the protection of sensitive data should be directed to Diane Dunning. The other datasets do not contain sensitive data that needs protecting.  

**Software creation and maintenance:** responsible for the creation, design, and installation of a software products and maintenance of the system (software update, error correction, enhancement of existing features).  
*Responsible Parties:* Martha Marien will produce and maintain the software associated with the meteorological dataset.  

**Instrumentation maintenance:** responsible for conducting tasks related to instruments such as installation, calibration, testing, and performing maintenance of instrumentation equipment.  
*Responsible Parties:* Martha Marien will maintain weather station which collects the meteorological data.  

**Data collection/ data generation:** responsible for data collection and creation, data entry, information processing, manipulation, and data generation.  
*Responsible Parties:* Martha Marien will make sure the meteorological data is generating from the station. Sam Singer will conduct the bird survey on the northern bank, Arthur Chapman will conduct the bird survey on southern bank. Patrick Pullman will collect water samples at sites 1-7 and Cathy Thompson will collect water samples at sites 8-17. Barbra Hubble will conduct all in person interviews about the use of the Brian Booth Wetlands.  

**Data organization:** responsible for maintaining the data in an organized data structure so that it is easy to find by creating consistent and defined folder structure and naming conventions. Responsible for saving the data in the appropriate formats.  
*Responsible Parties:* Martha Marien will organize the meteorological data. Sam Singer will organize the bird survey. Patrick Pullman and Cathy Thompson are each responsible for their samples and Patrick Pullman is responsible for merging the data. Barbra Hubble will organizes the wetlands survey.   

**Metadata generation:** responsible for generating metadata (data description), documentation, using the metadata standards or templates specified in the Data Management Plan.  
*Responsible Parties:* There are different conventions depend on the specific dataset. The metadata standards for each dataset are defined below.

*Meteorological Data:* All metadata will be recorded using a metadata standard in the field (EML Ecological Metadata Language). Martha Merien will be responsible for documenting the data in this format.  

*Bird Survey:* A plain text read me file documenting the spreadsheet will be created by Sam Singer and Arthur Chapman. Sam Singer will be responsible for the methods part, Arthur Chapman will be responsible for the rest (variable definitions, defining acronyms, etc).  

*Water Quality Data:* Data will be documented with a lab specific template found in the shared folder "R:\projects\BrBoMaster\WaterQ\Documents\Lab_standards.txt". Lab notebooks should follow all of the specifications for the lab. Patrick Pullman and Cathy Thompson will generate metadata for samples.   

*Wetlands Survey:* Documentation about the interviews, including consent forms, will be created and managed by Diane Dunning.  

*Maps Data:* Julie Reynolds will be responsible for documenting the maps using FSGC metadata standards.    

**Quality control:** responsible for performing quality assurance and quality control. It involves testing, reviewing, cleansing of data, calibration, correcting errors, data remediation, and documentation of quality control on the data points.  
*Responsible Parties:* Rick Rogers will manage the meteorological data, Sam Singer will manage the bird survey data, Patrick Pullman and Cathy Thompson will manage the water quality data, Barbra Hubble is responsible for the wetlands survey dataset, and the map data will be managed by Julie Reynolds.  

**Data analysis:** responsible of various activities related to data analysis such as examining, analyzing, sorting, aggregating, transforming, modeling, visualizing, validating, presenting, to answer research questions.  
*Responsible Parties:* Julie Reynolds will be responsible for the creation of the maps, Rick Rogers is responsible for the meteorological data analysis, Sam Singer and Arthur Chapman will work on the bird survey data, Patrick Pullman and Cathy Thompson will work on the water quality data, Barbra Hubble and Henry Cortez will work on the wetlands dataset.  

**Archiving and preservation:** responsible for assuring archiving and storage, preservation and access to data (and associated metadata) long term (e.g. in a repository or managed internally).  
*Responsible Parties:* Rick Rogers will preserve the various meteorological dataset versions, Sam Singer will preserve all of the bird survey data, Patrick Pullman will preserve the water quality data, Barbra Hubble will preserve the identified and de-identified wetlands surveys, Bethany Barnard will preserve the map data.  



Change Barbra to "Barbara"
Change all file locations to be inside quotations.
