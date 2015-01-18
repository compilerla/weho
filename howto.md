---
layout: page
title: "Part 4: How-to Open Data?"
---

## Defining Value
Starting with the data that will bring the most value early on will give credibility and early quick wins to your program. High value comes in the form of internal and external value. Certain datasets create internal value within your organization by reducing information requests or saving time creating reports. Other datasets create external value by facilitating civic engagement.

What will create internal value?:

* Is the dataset aligned with the department’s core function / Degree to which publishing this data furthers the core mission of the department?
* Is the dataset a direct or indirect source of a department’s Headline Performance Measure(s) and/or Supporting Measure(s)?
* Will posting the data result in administrative time saved for a department(s)? 
* For instance, as departments often spend substantial time and resource complying with California Fair Records Act (CFRA) requests -- or so called, FOIA at the federal-level -- there may be an opportunity to stop spending time responding to requests for this particular information?)
* Is the data already collected and readily accessible so as not to require new or additional business processes?
* Is the data used across departments and does its publication facilitate collaboration?
* Will publishing this dataset enable the retirement of a legacy system or database?

What will create external value?:

* Is the data typically used when deciding policies that impact residents’ quality of life?
* Will publishing this dataset allow a business or resident to perform a process more efficiently and/or effectively?
* Is Los Angeles City the only source of the data?
* Does the data contribute to civic engagement?
* Does the data create economic opportunity?
* Will publishing this dataset make the department more accountable and/or responsive by improving/increasing the public's knowledge of its operation?

### Data Quality & Standards & Permanence
* Archival Data: When possible, departments should consider what undigitized, archival data they have available to publish. Not only would these kinds of releases minimize CFRA requests, but they would also help put current data in context and support new research. Such archival material can be informed by the same kind of prioritization process used for general data release as defined in Part 3.
* Permanence: Once City data has been published and released to the public; it is inevitable that developers, both internal and external to the City, will utilize your department’s data to provide value to their applications, reports, and business decisions.  However, if a department must delete a dataset that has been published for public consumption, prior to deletion, they must obtain approval to delete the dataset from the Mayor’s Office – mayor.opendata@lacity.org.  The Mayor’s Chief Data Officer, or a designated Mayor’s Office representative will work with the department to review the request, and develop a plan to notify/respond to users who have grown to depend on the data’s availability.  
* Unique Identifiers: Departments should use publicly visible, non-proprietary unique identifiers for any entities (individuals, entities, or locations) that are commonly referred to in their data sets (e.g. for Recs and Parks, one might be Park IDs). Unique identifiers make it easier to perform multi-set analysis.
* APIs: Through the open data portal, all public datasets will be accessible through the built-in Application Programming Interface (API); this API enables developers to have bulk access to the data through their own applications. If an application a department already maintains is available as an API, the data should still be archived in a recurring manor on the Open Data Portal. (Trainings are available on automating this process.) Departments are then also asked to include in the metadata a link to the API, so the public could directly view more up-to-date information.

### Metadata & Attribution/Licensing

There are four general types of metadata that exist: 

* Administrative metadata is the most common and is produced in data collection, production, publication, and archiving. 
* Structural metadata describes a dataset’s structure, including its format, organization, and variable definitions. 
* Reference/descriptive metadata is a broad term that mostly involves descriptions of methodology, sampling, and quality.
* Behavioral metadata records to the reactions and behaviors of the dataset’s users. 

For each dataset published, the providing department must, at a minimum, provide values for all of the metadata elements as defined in the latest version of the DublinCore Metadata Element Set. In addition, the department must provide the metadata element” frequency” which must correspond to a value contained in the DublinCore Collection Description Frequency Vocabulary. Please see the table in APPENDIX E for a list of required metadata elements for data sets as of the publication of this technical standard. 

#### Metadata Formats: 
Popular Machine-readable, open formats for communicating metadata include XHTML, XML, JSON and RDF. Socrata natively supports data.json (JSON - JavaScript Object Notation) so any datasets managed through Socrata will be automatically exposed correctly in json format. Socrata also supports all the extended metadata fields through custom metadata features.

#### Controlled Vocabulary: 
For many fields (frequency, license, and data owner are examples), there is an option to enforce a controlled vocabulary rather than free text. Controlled vocabulary has two benefits: it helps with tracking, search, and summary by ensuring consistent language; and it could support compliance by making it easier for data providers to provide appropriate metadata. 

#### Metadata Standard:
 https://docs.google.com/a/socrata.com/spreadsheets/d/1wvJD4xGepkm24bopXSjYK4rlWrK0faEv8uKkyeognOs/edit?usp=sharing 

#### Attribution and Licensing: 
Although copyright law varies from jurisdiction to jurisdiction, the U.S. Copyright Act explicitly does not include federal government works, and is silent on U.S. state and local government works. This, coupled with the additional complexities of copyright law (and ownership of various types of government data), mean special attention should be applied to all government data and the ease of its legal re-use. If the government data in question is not explicitly in the worldwide public domain, it should be given an explicit public domain dedication [such as the Creative Commons CC0 statement or a Open Data Commons Public Domain Dedication and License (PDDL)—both of which combine a waiver and a license].

#### Citations: 
Departments are asked to clearly and effectively identify an individual data source and identify the unit of government which created or maintains the data. Where data users are actually transforming government data in some way, encouraging the proper citation of government data will allow end users to distinguish between problems with government data quality and intermediary data quality by providing a clear route back to the original source of the data.

### Technical Resources & Trainings
The City maintains a robust and growing list of technical documentation and trainings, on topics ranging from data automation and ingress to replacement and formatting. 

https://sites.google.com/a/lacity.org/datala/open-data-1/

Additionally, this resources features tools and tips on doing more advanced data science and analytics, as well as a calendar of on-site trainings, which will be free and open to any participate of the open data program.

### Contact and Support: 
If further support is needed, please contact ITA Data Leadership and the CDO, and they will direct you to the correct resource: mayor.opendata@lacity.org. Reaching out to those parties first is essential to ensure the City keeps coordinated communications with various partners.



