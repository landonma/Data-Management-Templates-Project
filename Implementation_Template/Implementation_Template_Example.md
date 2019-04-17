# Oregon-State-Data-Management-Plan
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

Rationale: bad data management practices increase the chances of conflict among the members of a research project. All projects should have a data management plan, regardless of the size of the project, and regardless of the funding source of the project.


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

###### *Instructions*  
*[Define datasets that will be created during this project, and group them according to different management needs. Describe relevant general information about the data groups: are they observational, experimental, simulation, model output or assimilation datasets; How will they be collected? How much data is expected?]*  
###### *Text*

Five groups of datasets will be generated during the course of this project.

1. Meteorological Group
	Type of dataset: Observational  
	Collection strategy: *[blank]*  
	Amount of data expected: 200 days of atmospheric data  

2. Bird Survey Group
	Type of dataset: *[observational, experimental, simulation, model output, assimilation…]*  
	Collection strategy: *[blank]*  
	Amount of data expected:   

3. Water Quality Group
  Type of dataset: *[observational, experimental, simulation, model output, assimilation…]*  
	Collection strategy: *[blank]*  
  Amount of data expected: *[blank]*  

4. Wetlands Survey Group  
  Type of dataset: *[observational, experimental, simulation, model output, assimilation…]*  
  Collection strategy: *[blank]*  
  Amount of data expected: *[blank]*  

5. Area Map Group  
  Type of dataset: *[observational, experimental, simulation, model output, assimilation…]*  
  Collection strategy: *[blank]*  
  Amount of data expected: *[blank]*  

##### Rationale and resources
These groups should be referred to throughout the document when different management needs arise.


## Data Collection
###### *Instructions*  
*[Information relevant to how data will be collected, captured or created]*

**Sampling sites:** *[Include information with description of sampling sites including important data about them such as location, official names to be referred to, instrumentation in each sampling site, etc. ]*  

**Existing protocols:** *[Include the location of protocols relevant to the research that already exist, like lab safety protocols, sampling protocols, instrument installation protocols, etc. Include here all the contextual information relevant for the use of the protocol that is not explained in the protocol itself ]*  

1. Name: *[name of protocol]*  
2. Location: *[where to find the protocol]*  
3. Expected use: *[who should use the protocol, when]*  
4. Training: *[who will train new researchers. Who to ask when there are questions about the protocol.]*  

**New protocols:** *[For projects that involve the creation of routinely creating new protocols, describe the process of creating new protocols.]*  

1.  Process *[Defines the process to create the protocol]*  
2. Approval *[Process to approve the protocol, and who should approve it]*  
3. Tools *[If special tools will be used to create the protocol, specify]*  
4. Storage *[Where it should be saved, with which file naming strategy]*  
5. Update *[How to update the protocol]*  
6. Expected use *[Who should use the protocol, and for which circumstances]*  

**Instrumentation:** *[Include relevant information about the instruments that will be used to collect data, like where to find instructions, maintenance to ensure that the sensors will work correctly, etc.]*  

**Software:** *[Include relevant information about the software that will be used to generate data. Where to access the documentation. Intellectual property information about the software to be aware of. ]*  


##### LAB NOTEBOOKS

##### ELECTRONIC DATA


## Data Documentation
###### *Instructions*  
*[Describe how data will be documented throughout the project]*

###### *Text*  
Data will be documented throughout the research process using the following tools:

**Lab notebooks:** *[If the project will use lab notebooks to document their lab procedures, include here best practices to keep them in the lab]*

Details about experiments and work in a lab are quickly forgotten unless they are written down. Be diligent in writing information into notebooks. Follow best practices:  
- Lab notebooks will always be bound notebooks. Blank notebooks can be found in *[blank]*. Number and date the notebook when you begin with a new one.  
-	Pages should always be numbered.
-	Write legibly and in a language understood by everybody in the lab.
-	Error correction: incorrect information should be visible, but clearly marked as incorrect.  Date, sign and explain the correction. Do not erase entries or blot them out.
-	Printed documentation added to the lab notebook should be attached permanently.
-	Note where all electronic files associated with the experiment are located.
-	All entries should be consecutive. Always record dates.
-	Backup: at the end of the day *[blank]* [scan, photograph…] the pages of the notebook that you worked on, and store them in *[blank]*

**Templates:** *[If the project will use templates to document datasets, include here instructions about where to find the templates and how to use them]*  

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



- Datasets will be shared internally             **_[specify when researchers are expected to share their datasets. Some examples: as soon as possible after the data is collected/at the end of the sampling season/6 months after it is collected/on January of each year/when a researcher of the Project requests it ]_**.

- Datasets will be shared internally with         **_[who? Some examples: all the members of the team/members of the team approved by the IRB/the data manager of the project/the researcher who requested the dataset]_**.

- Datasets will be shared internally in                   format **_[is there an expected format? For example excel, or csv, or spss, or…]_**.

- Datasets will be shared internally                 **_[at which quality level? For example: after a quality control level has been assigned to each point following the schema in X / after following the protocol X for quality control/at any quality control level, as long as the documentation clarifies the quality control procedures that have been followed /only if all the data points have been subject to the whole quality control process outlined in X]_**.

- Datasets will be shared internally accompanied of                **_[which documentation? For example: a readme file outlining at least the methods followed for data collection, the quality control procedures that have been followed, and a data dictionary/documentation using the template X/documentation using the metadata template X]_**.

- Datasets will be shared internally by                   **_[how are the datasets going to be delivered? For example: by e-mail/by depositing them in Box/Google drive/external hard drive/shared drive/website]_**.

- When a member of the Project uses a dataset shared by another member of the team        **_[how will the use be notified? For example: a courtesy e-mail will be sent to the contact person/no notification will be needed at this stage/the member of the Project using the shared data will write his/her name in a log]_**.

- When a new version of a dataset is generated, it will be notified to the other members of the Project that may want to use the dataset by             **_[example: sending a general e-mail to the whole group/documenting in the documentation file the new version and sending individual e-mails to the members of the team that are known to be using the dataset]_**.

**_[Include other workflow details that will be useful if necessary. For example, there may be details in the data management plan that can be outlined or detailed here. For example, when will the datasets be made publicly available? Who will decide when to make the dataset available if there are several researchers working with them?]_**



## Data Use



## Protection for Sensitive and Confidential Data



## Management of Physical Samples



## Data Publication

##### Acknowledgment of Data Use


Rationale: Most of the data management responsibilities outlined in the final section require a lot of time and effort. Often, datasets are shared within members of the same project and the use of these datasets improves or makes possible scholarly outcomes  such as publications of articles, book chapters, presentations in conferences, proceedings, etc. It is necessary to have a common understanding on how to acknowledge the role of data managers, data creators, data analysts in the research process. These roles may not be appropriate as manuscript authors, but there are many other options. Acknowledging these roles is not a legal matter (no law requires it), but it is an ethical one. Responsible conduct of research involves acknowledging other people’s roles in managing data. Acknowledging the roles may also have an impact of the careers of researchers involved.    


**_[Decide what are the procedures that you will follow to acknowledge data management roles, and if there are any preferred methods. This template lists the options in order: options that follow best practices are noted at the beginning, while practices that we discourage are noted at the end. We use here “data management” as a general term, but consider changing it for more specific roles. For example, you may want to consider offering co-authorship to the researchers involved in data collection and data quality control as authors in data publications, and adding the researchers involved in instrumentation maintenance in the acknowledgements]_**


All members of the Project involved in roles related to data management will be acknowledged in some way. Specifically:



- Members of the Project that were involved in data management **_[change to a more specific role]_** will be offered co-authorship to papers that make use of their data. Co-authorship will require participation in the interpretation of the data, writing, or critical review of the manuscript, approval of the final manuscript. **_[if the group defines authorship using a specific set of criteria, include a link to these criteria here. A few examples of current definitions of authorship can be found in https://publicationethics.org/resources/discussion-documents/what-constitutes-authorship-june-2014]_**. The offer for co-authorship may be accepted or declined.


- Datasets will be published separately from the research in a repository or as an article in a data journal **_[change if there are more discipline specific options]_**. Members of the Project with a significant data management contribution will be listed as co-authors in the data publication. Every member of the Project that makes use of the published datasets will cite the dataset and list it in the reference list in their publications.  



- When possible, publications will be made in journals that use the CRediT authorship taxonomy (http://docs.casrai.org/CRediT) or similar. The roles of each of the members of the Project involved in data management will be documented using the appropriate roles.

## Data Archival



## Roles and Responsibilities
Rationale: Data management takes time and effort. In order to not oversee any important data management action, it should be clear to all the members of the team who is responsible for each of them.


##### Role definitions: **_[adapt the definition of each of the roles for the Project. These roles are defined so that this document will not need to be adapted every time that there are changes within the Project team. These definitions should reflect as accurately as possible the roles in the project. For example, if the project will have Postdocs but not technicians, rename the Researcher role to Postdoc. For example, if there are going to be two kinds of students (field students and lab students) that will have different data management roles, these should be outlined here. For example, if the project is going to have a data manager, outline the role here.]_**


**Principal Investigator (PI):** leads the Project. It is usually designated by the funder. If there is no funder or the funder does not designate the principal investigator, it will be person providing leadership to the Project.

**Faculty Investigator:** they actively perform research on all or a part of the research Project. They may provide active mentorship to students.

**Team member:** they contribute to the scientific development or execution of a study in a substantive, measurable way (research/postdoctoral fellows, technicians, associates and consultants).

**Student:** member of the Project pursuing a degree. Undergraduate, master, PhD or others

##### Responsibilities **_[adapt the definition of each of these responsibilities to the Project. Add more, or remove if necessary. Decide who (which role) is going to be responsible for each of these]_**




**DMP Implementation:** responsible for ensuring Data Management Plan and the Internal Data Sharing Plan move from planning into implementation; ensure that any practices, responsibilities, policies outlined in the plan are followed; ensure that new members of the Project will receive data management training; responsible for maintaining the Data Management Plan and the Internal Data Sharing Plan up to date, and making sure that all members of the Project understand and are prepared to apply the changes.


 Responsibility of: **_[complete with one of the roles defined above]_**


**Access control:** responsible for regulating access to data based on the roles of the authorized user, whether from the project or not. Access is the ability to perform a specific task, such as view, create, or modify a file. Responsible for granting access to data by members outside of the project when requested during the duration of the project.


Responsibility of: **_[complete with one of the roles defined above]_**

**Protection of sensitive and protected data:** responsible for complying with applicable laws and regulations, institutional policies, and ethical principles governing the conduct of human subjects research, sensitive and protected data.


Responsibility of: **_[complete with one of the roles defined above]_**


**Software creation and maintenance:** responsible for the creation, design, and installation of a software products (e.g. code writing) and maintenance of the system (software update, error correction, enhancement of existing features).


Responsibility of: **_[complete with one of the roles defined above]_**


**Instrumentation maintenance:** responsible for conducting tasks related to instruments such as installation, calibration, testing, and performing maintenance of instrumentation equipment.


Responsibility of: **_[complete with one of the roles defined above]_**


**Data collection/ data generation:** responsible for data collection and creation (research, locate, identify, and measure), data entry, information processing (transcribing and manipulation), data generation (prototyping, models, and database).


Responsibility of: **_[complete with one of the roles defined above]_**


**Data organization:** responsible for maintaining the data in an organized data structure so that it is easy to find (i.e. folder structure, file naming conventions). Responsible for saving the data in the appropriate formats.


Responsibility of: **_[complete with one of the roles defined above]_**


**Metadata generation:** responsible for generating metadata (data description), documentation, using the metadata standards or templates specified in the Data Management Plan.


Responsibility of: **_[complete with one of the roles defined above]_**


**Quality control:** responsible for performing quality assurance  and quality control. It involves testing, reviewing, cleansing of data, calibration, correcting errors, data remediation, and documentation of quality control on the data points.


Responsibility of: **_[complete with one of the roles defined above]_**


**Data analysis:** responsible of various activities related to data analysis such as examining, analyzing, sorting, aggregating, transforming, modeling, visualizing, validating, presenting, to answer research questions.


Responsibility of: **_[complete with one of the roles defined above]_**


**Archiving and preservation:** responsible for assuring archiving and storage, preservation and access to data (and associated metadata) long term (e.g. in a repository, or managed internally).


Responsibility of: **_[complete with one of the roles defined above]_**

##### *Role definitions:*
*[adapt the definition of each of the roles for the Project. These roles are defined so that this document will not need to be adapted every time that there are changes within the Project team. These definitions should reflect as accurately as possible the roles in the project. For example, if the project will have Postdocs but not technicians, rename the Researcher role to Postdoc. For example, if there are going to be two kinds of students (field students and lab students) that will have different data management roles, these should be outlined here. For example, if the project is going to have a data manager, outline the role here.]*


**Principal Investigator (PI):** leads the Project. It is usually designated by the funder. If there is no funder or the funder does not designate the principal investigator, it will be person providing leadership to the Project.

**Faculty Investigator:** they actively perform research on all or a part of the research Project. They may provide active mentorship to students.

**Team member:** they contribute to the scientific development or execution of a study in a substantive, measurable way (research/postdoctoral fellows, technicians, associates and consultants).

**Student:** member of the Project pursuing a degree. Undergraduate, master, PhD or others
%%
##### *Responsibilities* **_[adapt the definition of each of these responsibilities to the Project. Add more, or remove if necessary. Decide who (which role) is going to be responsible for each of these]_**




**DMP Implementation:** responsible for ensuring Data Management Plan and the Internal Data Sharing Plan move from planning into implementation; ensure that any practices, responsibilities, policies outlined in the plan are followed; ensure that new members of the Project will receive data management training; responsible for maintaining the Data Management Plan and the Internal Data Sharing Plan up to date, and making sure that all members of the Project understand and are prepared to apply the changes.


 Responsibility of: **_[complete with one of the roles defined above]_**


**Protection of sensitive and protected data:** responsible for complying with applicable laws and regulations, institutional policies, and ethical principles governing the conduct of human subjects research, sensitive and protected data.


Responsibility of: **_[complete with one of the roles defined above]_**


**Instrumentation maintenance:** responsible for conducting tasks related to instruments such as installation, calibration, testing, and performing maintenance of instrumentation equipment.


Responsibility of: **_[complete with one of the roles defined above]_**


**Data collection/ data generation:** responsible for data collection and creation (research, locate, identify, and measure), data entry, information processing (transcribing and manipulation), data generation (prototyping, models, and database).

Responsibility of: **_[complete with one of the roles defined above]_**
