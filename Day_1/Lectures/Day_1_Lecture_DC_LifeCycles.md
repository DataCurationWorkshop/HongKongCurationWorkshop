#“Data Curation Life Cycles and Tools”


#Outline

0. Introduction (20 min, NW)
1. Archives and Records Management for Data Curation (NW) 
*2. Review of lifecycle models (DCC, DataOne... , workflows from the SBDC project?) (20 min, AT)*
3. Making the lifecycle actionable (Checklists, Curation Profiles, Significant Properties) (20 Min, AT)
4. Making the lifecycle actionable: the importance of stable identifiers (NW)
5. Scholarly Communications Issues: Data Citation, Publication, and Linking

## 2. The Data Lifecycle

While many curatorial steps _can_ take place long after a dataset's original point of creation or collection, data curation is generally more effective when conducted as an on-going process.  As the DCC writes, 

>It is a common misconception that data is created or captured and then passed on to someone else to curate. In fact, much of the most crucial information required for effective long-term curation and reuse must be captured at the conceptualisation and collection stages. [from the DCC FAQ](http://www.dcc.ac.uk/resources/curation-lifecycle-model/lifecycle-model-faqs#sthash.I5US5DyT.dpuf)

Life cycle models present us with a way of atomizing data collection, use, analysis and preservation into component stages, and then identifying individual curatorial tasks that can or should be completed at each point. Further, a life cycle approach to curation is necessary because:
>- Digital materials are fragile and susceptible to change from technological advances throughout their life cycle, i.e. from creation onwards;
>- Activities (or lack of) at each stage in the life cycle directly influence our ability to manage and preserve digital materials in subsequent stages;
>- Reliable re-use of digital materials is only possible if materials are curated in such a way that their authenticity and integrity are retained.  (Pennock, 2007)


There are numerous life cycle models; for this workshop we'll focus on two of the more popular general models, one from the Digital Curation Centre (DCC) and one from Data One, and one domain-specific model from the SBDC project at the University of Illinois.

## 2.1 The DCC Lifecycle Model

[image]

The DCC model divides curatorial tasks into three interlinked categories, all of which are (quite literally) centered around data:

#### 2.1.1 Full lifecycle actions

These are actions that continue throughout the lifespan[link to lifecycle def in introduction] of a dataset, and require on-going attention from the curator.  These tasks include:

- _Preservation Planning_

>Plan for preservation throughout the curation lifecycle of digital material. This would include plans for management and administration of all curation lifecycle actions.

- _Community Watch and Participation_

>Maintain a watch on appropriate community activities, and participate in the development of shared standards, tools and suitable software. 

- _Curate and Preserve_

>Be aware of, and undertake management and administrative actions planned to promote curation and preservation throughout the curation lifecycle.

- _Description and Representation Information_

>Assign administrative, descriptive, technical, structural and preservation metadata, using appropriate standards, to ensure adequate description and control over the long-term. Collect and assign representation information required to understand and render both the digital material and the associated metadata.

[See more](http://www.dcc.ac.uk/resources/curation-lifecycle-model#sthash.QOx0GL9t.dpuf)

We'll talk more about these activities in coming sessions.

#### 2.1.2 Occasional actions 

These actions may need to be done repeatedly, but only every once in a while.  They include:

- _Reappraisal_

>Return data which fails validation procedures for further appraisal and re-selection.

- _Migration_

>Migrate data to a different format. This may be done to accord with the storage environment or to ensure the data's immunity from hardware or software obsolescence. 

- _Disposal_

>Dispose of data, which has not been selected for long-term curation and preservation in accordance with documented policies, guidance or legal requirements.  Typically data may be transferred to another archive, repository, data centre or other custodian. In some instances data is destroyed. The data's nature may, for legal reasons, necessitate secure destruction.

[See more](http://www.dcc.ac.uk/resources/curation-lifecycle-model#sthash.Iq4isJfb.dpuf)

#### 2.1.3 Sequential actions  

These actions mirror the general workflow of research, and each stage entails specific curatorial tasks.  These include:

- _Conceptualise_

>Conceive and plan the creation of data, including capture method and storage options.

- _Create or Receive_

>Create data including administrative, descriptive, structural and technical metadata. Preservation metadata may also be added at the time of creation. Receive data, in accordance with documented collecting policies, from data creators, other archives, repositories or data centres, and if required assign appropriate metadata.

- _Appraise and Select_

>Evaluate data and select for long-term curation and preservation. Adhere to documented guidance, policies or legal requirements.

- _Ingest_

>Transfer data to an archive, repository, data centre or other custodian. Adhere to documented guidance, policies or legal requirements.

- _Preservation Action_
>Undertake actions to ensure long-term preservation and retention of the authoritative nature of data. Preservation actions should ensure that data remains authentic, reliable and usable while maintaining its integrity. Actions include data cleaning, validation, assigning preservation metadata, assigning representation information and ensuring acceptable data structures or file formats.

- _Store_

>Store the data in a secure manner adhering to relevant standards.

- _Access, Use and Reuse_

>Ensure that data is accessible to both designated users and reusers, on a day-to-day basis. This may be in the form of publicly available published information. Robust access controls and authentication procedures may be applicable.

- _Transform_

>Create new data from the original, for example: by migration into a different format, or by creating a subset, by selection or query, to create newly derived results, perhaps for publication

[more from DCC](http://www.dcc.ac.uk/resources/curation-lifecycle-model#sthash.Iq4isJfb.dpuf)

Note that in the DCC model, the majority of work with data _prior_ to it's existence in an archive or repository takes place within the "Conceptualise" and "Create or Receive" stages.  While this may make the DCC Model particularly relevant for academic librarians and data curators, it does make it more less relevant to curators and researchers seeking to push curatorial activities "upstream" in the overall research process (see Wallis et al, 2008 for further explanation on the necessity of this).  The Data One and SBDC models presented below attempt to integrate curatorial and research activities a bit more holistically.

## 2.2 The Data One Model

The Data One model is considerably simpler than the DCC model, and consists of 8 sequential, but continuous, stages: 

>_Plan:_ description of the data that will be compiled, and how the data will be managed and made accessible throughout its lifetime<br>
_Collect:_ observations are made either by hand or with sensors or other instruments and the data are placed a into digital form<br>
_Assure:_ the quality of the data are assured through checks and inspections<br>
_Describe:_ data are accurately and thoroughly described using the appropriate metadata
standards<br>
_Preserve:_ data are submitted to an appropriate long-term archive (i.e. data center)<br>
_Discover:_ potentially useful data are located and obtained, along with the relevant information about the data (metadata)<br>
_Integrate:_ data from disparate sources are combined to form one homogeneous set of data that can be readily analyzed<br>
_Analyze:_ data are analyzed 

(From the DataOne Best Practices Primer)

[image]

Many of these stages are similar to the sequential steps described by the DCC model -- however we do note that the Data ONE model is intended to be viewed through the perspective of an independent researcher or research team undertaking curatorial tasks on their own or in occasional collaboration with a data center or archiving service. Consequently, many of the recommendations are aimed at researchers rather than LIS practitioners. 

## 2.3 SBDC Workflow for Geobiology: Workflow documentation as a curatorial tool

The Site-Based Data Curation (SBDC) project at the University of Illinois has been developing a framework of policies and best practices for the curation of digital research data collected from _scientifically significant sites_, using the interdisciplinary field of geobiology as an initial case study. We have found that extremely detailed workflow documentation can help practitioners identify important curatorial "points of intervention", or stages within a research project, at which data products must be captured for later sharing and reuse.

Thus, rather than aiming to create an idealized lifecycle model applicable to all fields of scholarship (as in the DCC and DataOne models do), we have created an extremely domain- (or even project-) specific workflow, that fully expresses the specificities unique to a particular kind of research.  We believe that the creation of domain- or project-specific workflows can be helpful curatorial tools in cases in which practitioners are working extensively with researchers from one scholarly domain, or one research team.

In this example, we worked extensively with Bruce Fouke, a geobiologist and co-PI of our project, to first inventory all data products (e.g. digital data such as spreadsheets, databases, gene sequences, field notes, field photographs, and more) from one field project, and then document a) how those data products were created, and b) how those data products were interlinked. The SBDC team's later work curating those data products was also identified.

The resulting workflow has 6 stages: Planning, Fieldwork, Processing & Analysis, Data Assessment, Standardizing and Packaging.  

[image of workflow]

While these aren't substantially different from the DCC or Data One models, we do note our inclusion of and emphasis on field work (or data collection) as its own stage.  Further,
we have tried to show the dependencies between different data products produced at different stages of research and curation:

[image of key documents and data products]

Though this initial workflow is specific to the field of geobiology -- and indeed, Dr. Fouke's particular field practices -- we are working with other researchers in other fields to document their research and curation workflows as well, and we hope that the resulting workflows can be altered and used by others.  We will discuss the workflow documentation process further in today's lab session.


## Bibliography

### Data and Digital Curation Lifecycle Models

**DCC**

Higgins, S. (2008). The DCC curation lifecycle model. International Journal of Digital Curation, 3(1), 134-140. [PDF](http://www.ijdc.net/index.php/ijdc/article/viewArticle/69)

[Web resources on the DCC lifecycle model](http://www.dcc.ac.uk/resources/curation-lifecycle-model)

**Data ONE**

[DataONE general resources and best practices](https://www.dataone.org/best-practices)

Strasser, C., Cook, R., Michener, R., & Budden, A. (N.D.). Primer on Data Management: What you always wanted to know (but were afraid to ask). Data One. [PDF](https://www.dataone.org/sites/all/documents/DataONE_BP_Primer_020212.pdf)

**Other**

Ball, A., 2012. Review of Data Management Lifecycle Models. Other. Bath, UK: University of Bath. [PDF](http://opus.bath.ac.uk/28587/1/redm1rep120110ab10.pdf)

Wallis, J. C., Borgman, C. L., Mayernik, M. S., & Pepe, A. (2008). Moving archival practices upstream: An exploration of the life cycle of ecological sensing data in collaborative field research. International Journal of Digital Curation, 3(1), 114-126. [PDF](http://www.ijdc.net/index.php/ijdc/article/viewArticle/67)

Haythornthwaite specificities paper

Pennock, M. (2007). Digital curation: A life-cycle approach to managing and preserving usable digital information. Library and Archives Journal, Issue 1. Retrieved (preprint) June 18, 2008 from http://www.ukoln.ac.uk/ukoln/staff/m.pennock/publications/docs/lib-arch_curation.pdf
