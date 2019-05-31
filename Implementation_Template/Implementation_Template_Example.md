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


The data management plan approved by the NSA can be found at the following location: "R:\Project\BrBoMaster\DMPMaster\Data_Managment_Plan_Approved.2019.01.05"
Contracts between OSU and the Oregon Parks department that involve data management can be found in "R\Projects\BrBoMaster\MasterAdmin\OSU_Contract_with_Oregon_Parks.2018.12.15.pdf"
All datasets contain unrestricted (based on the [OSU's Data Classifications](https://uit.oregonstate.edu/ois/data-management-and-classification-overview) data except the raw data from the Wetlands Survey subproject which contains sensitive information.

##### 1) Health and Value of the Brian Booth Wetlands
The aim of the project is use a wide range of disciplines to look at function and health of the Brian Booth Wetlands which lies along the Central Oregon Coast. To do this, twelve people from five departments and one government agency will collect five datasets looking at different aspects of the same area.

##### 2) Data Management Plan (DMP)
The data management plan for the project can be found in the shared R drive at "R:\projects\BrBoMaster\DMPMaster\DMP.latest.doc".  

##### 3) Data Description
 The datasets are as follow:

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
	Amount of data expected: 200 days of atmospheric data, less than 50MB of data  

2. Bird Survey Group
	Type of dataset: observational  
	Collection strategy: Bird Survey conducted around 17 sites by 2 people visiting each site twice   
	Amount of data expected: 34 csv tables, less than 50MB of data     

3. Water Quality Group
  Type of dataset: Observational  
	Collection strategy: Water samples collected at 8 sites by 2 people during mid-March then analyzed in the lab
  Amount of data expected: 64 csv tables and microscope Image, 100 to 200 MB of data    

4. Wetlands Survey Group  
  Type of dataset: Observational  
  Collection strategy: In person survey questionnaires conducted at the park  
  Amount of data expected: 30 questions survey from 50 participants, less than 50 MB of data  

5. Area Map Group  
  Type of dataset: Observational
  Collection strategy: USGS Downloads  
  Amount of data expected: One geodatabase with 10 to 15 shape files 100 to 200 MB of data


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
4. Training: Shauna Thompson, the lab manager, will handle training    

Water Quality Group (2):
1. Name: Water Sample Analysis  
2. Location: R:\projects\BrBoMaster\WaterQ\Documents  
3. Expected use: Kathy Thomas and Patrick Pullman   
4. Training: Shauna Thompson, the lab manager, will handle training

Wetlands Survey Group:
1. Name: Questionnaire Survey Protocol  
2. Location: R:\projects\BrBoMaster\ !!  
3. Expected use: Barbara Hubble    
4. Training: Barbara Hubble will train as necessary

**New protocols:** *[For projects that involve the creation of routinely creating new protocols, describe the process of creating new protocols.]*  

Bird Survey Group:
1. Process: Modified Breeding Bird Survey  
2. Approval: Sam Singer will approve the protocol  
3. Tools: GPS Unit, Understanding of the Breeding Bird Survey
4. Storage:  R:\projects\BrBoMaster\Birds  
5. Update: A review of the modified breeding bird survey will be conducted after the first set of data collection. Updates or suggestions necessary after this point should go through Sam Singer
6. Expected: use Sam Singer and Arthur Chapman will use a breeding bird survey adjusted for smaller areas  

**Instrumentation:**
1. Meteorological Group: The WxPRO weather station with onboard memory will be used to collect the meteorological reading for the project. The user-manual provide by the company can be found with the unit which is stored in the CEOAS Machine and Technical Development Facility. The station contains enough onboard memory to last the duration of the study but should be checked monthly for functionality. The data should be checked and logged every 2 months by a member of the meteorological group.

2. Bird Survey Group: GPS units and binoculars are stored in Sam Singer's office (538a Nash Hall). Charging/USB cable and instructions are provide in the GPS unit's box.

3. Water Quality Group: The materials for the water collection kits can be found in Shauna Thompson's lab (Gilbert 193). Provided with the kit are instructions on how to collect ideal samples. This lab also contains the equipment for processing and recording the samples once they are obtained. Talk to Shauna or one of the lab technicians before using any microscopes and for more instructions.     

4. Wetlands Survey Group: Please see Barbra Hubble for any necessary instruments.  

**Software:** *[Include relevant information about the software that will be used to generate data. Where to access the documentation. Intellectual property information about the software to be aware of. ]*  
1. Meteorological Group: Up-to-date Software for the meterological data can be found in the group's GitHub Repository: https://github.com/OSUMetero/BrianWetlands  

2. Bird Survey Group: Software for importing the data from the GPS units can be found on any computer in the Digital Earth Lab.  

3. Area Map Group: ArcGIS Pro is available on all computers in the Digital Earth Lab or through Citrix.  

## Data Documentation
###### *Instructions*  
*[Describe how data will be documented throughout the project]*

###### *Text*  
Data will be documented throughout the research process using the following tools:

**Lab notebooks for Water Quality Group:**

Details about experiments and work in a lab are quickly forgotten unless they are written down. Be diligent in writing information into notebooks. Follow best practices:  
- Lab notebooks will always be bound notebooks. Blank notebooks can be found in top drawer of the bench nearest the door in Gilbert 193. Number and date the notebook when you begin with a new one.  
-	Pages should always be numbered.
-	Write legibly and in a language understood by everybody in the lab.
-	Error correction: incorrect information should be visible, but clearly marked as incorrect.  Date, sign and explain the correction. Do not erase entries or blot them out.
-	Printed documentation added to the lab notebook should be attached permanently.
-	Save all images to the drive under R
-	All entries should be consecutive. Always record dates.
-	Backup: at the end of the day photograph the pages of the notebook that you worked on, and store them in the top drawer of your workstation

**Templates:** surveys,   

**Readme:** *[If the project will be documented using readme files, include expectations about where they will be created, and which information will be recorded in them.]*  

** Standards** link to the standards, tool for making them (ArcGIS)http://desktop.arcgis.com/en/arcmap/10.3/manage-data/metadata/creating-and-managing-fgdc-metadata.htm
EML tool -> Morpho or r packages (EMLassmplyline)


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

Level two data are the best data that a researcher could use. Level two data should not include data that have undergone quality control procedures that are subjective to the researcher. Level two data can look different for different data sets:

1. Meteorological Group: Level 2 datasets has been calibrated with the latest software but has not undergone statistical analysis.

2. Bird Survey Group: Level 2 datasets has been combined with all other surveys conducted up to this point and has identically naming conventions for species, site locations, units, ect...

3. Water Quality Group: The conventions for level 2 data for the lab can be found in the R drive at the following location: R:  

4. Wetlands Survey Group: Level 2 surveys are those that have been processed for missing information but have not been analyzed further. Both identified and de-identified versions should be available at this level.    

5. Mapping Group: Level 2 data are geodatabases with unified projections, units, ect... but lack further analysis or joining of layers.

**Level three (L3):** L2 data that have been analyzed to answer specific research questions. Typically, this is the data that will be used to create figures in a publication. For example, if a principal component analysis was used to analyze three years of temperature data and published in a figure as part of a peer-reviewed article.  


## File Organization

###### *Instructions*    


The file structure of the R drive should maintain the following general structure. It is the responsibility of the uploader to move the data from the current to the outdated folder before uploading the new dataset.

![alt text](https://landonma.github.io/filepath.png "File Structure for the R Drive")



## Formats
###### *Instructions*    
*[Describe preferred formatsto save information and data. Describe situations in which files should be changed from one format to a different one.See the guidance document for a list of preferred formats for long term preservation.]*

##### Rationale and resources




Formats that will be better at long term preservation are formats that are platform independent (can be accessed from Linux, Mac and Windows), in an open format (no proprietary formats), and character based (not in binary format). There can be exceptions to all of these for the right reasons. For example, some data standards that are widely used in some disciplines, like netCDFs, save data in binary format.  
See [eCommons: Cornell's Digital Repository. Recommended file formats](http://guides.library.cornell.edu/ecommons/formats) for a table with existing formats for different types of content, and their probability for full term preservation.



## Storage  



## Backup

The differential backups of the R server are created daily and stored on campus through the Information Services of OSU (https://is.oregonstate.edu/service/server-backup). These backups should be tested once every three months during the project by the person in charge of archiving the data for each project.

Cloud backups are encouraged as long as the material is de-identified and not publicly viewable. This maybe in the form of Box of private GitHub repositories.

## Workflow Internal Data Sharing
Rationale: setting expectations about how and when datasets will be shared internally will minimize conflict during the project.


- The meteorological dataset will be made available to everyone involved with the project on the shared drive at the following location; R:\projects\BrBoMaster\Metero\. The data will be available in csv format accompanied by XML documents which adhere to EML metadata standards. Datasets will be consistently updated and calibrated throughout the project by Martha Marien. As datasets are updated, no notification will be given. Raw data will only be uploaded if there are no processed version and otherwise can be requested by emailing Martha Marien.


- The bird survey dataset will be made available to everyone involved with the project on the shared drive at the following location; R:\projects\BrBoMaster\Birds. The dataset will be available in CSV format accompanied by text files which include the metadata. Datasets will be uploaded within two weeks of data collection by the individual who collected it. The first survey will be conducted in March and the second in May. Email notifications will be sent when the new datasets are uploaded.  


- The water quality datasets will be made available to everyone involved with the project on the shared drive at the following location; R:\projects\BrBoMaster\WaterQ.  Datasets will be available in CSV format with metadata in an accompanied text file. Datasets will be uploaded within two weeks of data collection and a notification will be sent via email.

- The de-identified wetland's survey will be made available to everyone involved with the project on the shared drive at the following location; R:\projects\BrBoMaster\Wet!!. The dataset will be available in CSV format with all necessary metadata in a text file. The dataset will be updated in two batches and a notification will be sent via email when a new batch is available.


## Data Use

Most of the projects use CSV (comma-separated values) as a means of storing the data. Any program can be used to open and edit these files (Excel, LibreOffice, Notepad++, ect) as long as the format and file extension are maintained.

## Protection for Sensitive and Confidential Data

Management of the sensitive material inside the Wetland Survey datasets is to be handled by Dianne Dunning. The details concerning the protection of the sensitive can be found in the following location and was approved by the Institutional Review Board at Oregon State on 2019-01-18 R !

## Management of Physical Samples

All physical samples collected by the water quality group will be handle in the Gilbert 193 lab according to the specifications laid out in the following document R: .

## Data Publication

##### Acknowledgment of Data Use

All members of the Project involved in roles related to data management will be acknowledged in some way. Specifically:

Members of the Project that were involved in data generation will be offered co-authorship to papers that make use of their data. This offer is required for any publications with data that is formally unpublished. After the first publication of a dataset this convention is not mandatory but is highly encouraged for the two years following the project's completion. Co-authorship will require participation in the interpretation of the data, writing, or critical review of the manuscript, approval of the final manuscript. The offer for co-authorship may be accepted or declined. When students (PhD or masters) accept co-authorship, the initiators of the article will commit to provide support and mentorship to the student, so that their role can be meaningful.

When possible, publications will be made in journals that use the CRediT authorship taxonomy (http://docs.casrai.org/CRediT) or similar. The roles of each of the members of the Project involved in data management will be documented using the appropriate roles. Members of the Project involved in data analysis will be acknowledged in the acknowledgment section in papers and publications. 󠄀

## Data Archival

Datasets will be published separately from the research in a repository on OSU's Scholars Archive. Members of the Project with a significant data management contribution will be listed as co-authors in the data publication. Every member of the Project that makes use of the published datasets will cite the dataset and list it in the reference list in their publications. Some datasets may wait until after the initial publication containing the results before being uploaded.

## Roles and Responsibilities
Rationale: Data management takes time and effort. In order to not oversee any important data management action, it should be clear to all the members of the team who is responsible for each of them.


#### Role definitions:  
**Principal Investigator (PI):**
Bethany Barnard is the PI and will coordinate with all of the separate parts.

**Faculty Investigator:**
Three OSU faculty members are assigned to three of the subprojects:  
Rogers, Rick is responsible for the Meteorological Data  
Singer, Sam is responsible for the Birds Census  
Williams, Wallace is responsible for the Water Quality Data  

Dunning, Diane is a Parks and Recreation Department employee and is responsible for the Wetland Interviews dataset.

**Team member:**  
Martha Marien is a technicians in the College of Earth, Ocean, and Atmospheric Sciences at OSU and will work on the meteorological dataset. Patrick Pullman is a Postdoc in the Department of Fisheries and Wildlife at OSU and will work on the bird survey dataset.  

**Student:**  
Five Oregon State University Students will be working on various projects. Arthur Chapman will work on the bird census. Cathy Thompson will work on the water quality data. Barbra Hubble and Henry Cortez will work on the wetlands survey. Julie Reynolds will work on the creation of the maps of the area.

#### Responsibilities
The responsibility below will be broken down by subproject.

**DMP Implementation:** responsible for ensuring Data Management Plan and the Internal Data Sharing Plan move from planning into implementation; ensure that any practices, responsibilities, policies outlined in the plan are followed; ensure that new members of the Project will receive data management training; responsible for maintaining the Data Management Plan and the Internal Data Sharing Plan up to date, and making sure that all members of the Project understand and are prepared to apply the changes.  
*Responsible Parties:* Bethany Barnard will make sure all the subprojects are coming together and abiding by the DMP    
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
