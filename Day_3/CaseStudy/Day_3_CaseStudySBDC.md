# The Site-Based Data Curation Project

## Overview

The Site-Based Data Curation (SBDC) project at the University of Illinois has been developing a framework of policies and best practices for the curation of digital research data collected _in the field from scientifically significant sites_, using the interdisciplinary field of geobiology as an initial case study. 

The SBDC framework will help researchers produce shareable, reusable data by:

1) capturing the context of data collection needed for reuse by researchers in multiple disciplines,
2) streamlining submission of reusable data to open repositories, and
3) organizing collections for access within and across field sites.

### About geobiology

Our initial case study has focused on the interdisciplinary field of geobiology, as conducted in the geothermal hot springs at Yellowstone National Park (YNP).  Geobiologists study the interactions between microbial organisms and the sediments they live in and generate.  The microbes living in the hot springs at YNP are particularly interesting for being _thermophiles_: they can only live in extremely hot temperatures.  Thus, YNP has become an important research locality for scientists interested in understanding how life on earth may have originally evolved (many think that it may have emerged from similar, ancient hot springs or undersea volcanic vents), or even how life may evolve on other planets.  Furthemore, there are quite a number of industrial applications to this work: _Taq polymerase_, an enzyme critical to DNA amplification, was first found and isolated from a bacterium living in the hot springs at YNP.

### About Yellowstone National Park

YNP was established as the USA's first national park in 1872, and is world famous for its numerous hot springs and geysers: the park includes more than 10,000 hydrothermal features, including more than 300 geysers.  The majority of the park is located within the eroded caldera of a (still active!) ancient volcano, which last erupted 174,000 years ago.  The site is still quite geologically active, and thus of enormous interest to a broad range of scientists:

>The park's geothermal system is the visible expression of the immense Yellowstone volcano; they would not exist without the underlying magma body that releases tremendous heat. They also depend on sources of water, such as the mountains surrounding the Yellowstone Plateau. There, snow and rain slowly percolate through layers of permeable rock riddled with cracks. Some of this cold water meets hot brine directly heated by the shallow magma body. The water's temperature rises well above the boiling point but the water remains in a liquid state due to the great pressure and weight of the overlying water. The result is superheated water with temperatures exceeding 400°F. [link](http://www.nps.gov/yell/naturescience/hydrothermalsystems.htm)

![image](Day_3/CaseStudy/YNPmap.png)

_Geothermal areas (red) and caldera (shaded) in Yellowstone National Park.
(courtesy NPS)_

## Minimum information guidelines:

Capturing context in the field is crucial for research on geothermal systems: all sampling locations need to be contextualized by their location relative to the feature vent, and by the water chemistry of the spring at the sampling point. These data points concretely situate sampling locations within a geothermal system, and can act as community recognized “anchor points” that help future researchers integrate diverse datasets.

In Spring 2013, we held a stakeholders' workshop to begin generating more specific metadata requirements for geobiology data. Working with geobiologists and resource managers, we developed the following minimum information guidelines for different aspects of geobiology work at YNP:

###MINIMUM INFORMATION ABOUT A FIELD TRIP

1. Full name(s) of PI/Investigators, all members of the field party
2. Permit number
3. Date and time range of campaign
4. Thermal Feature Name(s): list of locations sampling was conducted. For sites at YNP, we recommend that researchers use names from the NPS Thermal Inventory location name and ID number (corrected as needed)
5. Investigator Sample ID numbering scheme – a short description of your basic sample reference code structure
6. A free text description of the purpose of the field trip and the sampling plan specifics

###MINIMUM INFORMATION ABOUT A GEOTHERMAL VENT

1. GPS location at vent- up to 3X different types of input coordinates
2. Altitude (Elevation) at vent – in meters derived from topographical maps or separate GPS systems
3. Vent Water Temperature – with brief description of techniques, stats of data collection
4. Vent Water pH – with brief description of techniques, stats of data collection
5. A contextualizing field photograph that includes the vent of the thermal feature and its surrounding environment (i.e. single facies at mm-cm-m+ length-scale and specific position within the drainage system) with embedded digital information on sample sites and other information (not just a “marked” photo)
6. A short free text description of the site overall, including the condition of the vent and sampling sites

###MINIMUM INFORMATION ABOUT A SAMPLING SITE

For each sampling site, we recommend that researchers record:

1. Sample ID number
2. Sampling position relative to the vent – distance from vent and bearing to/from vent, and name of facies
3. Field photograph of the sampling site – shot at a length-scale that includes the specific sample within the thermal feature and its surrounding environment
4. Water temperature (for water samples)
5. pH (for water samples)

## Process modeling for Geobiology: Workflow documentation as a curatorial tool

After developing s

We have found that extremely detailed workflow documentation can help practitioners identify important curatorial "points of intervention", or stages within a research project, at which data products must be captured for later sharing and reuse.

Thus, rather than aiming to create an idealized lifecycle model applicable to all fields of scholarship (as in the DCC and DataOne models do), we have created an extremely domain- (or even project-) specific workflow, that fully expresses the specificities unique to a particular kind of research.  We believe that the creation of domain- or project-specific workflows can be helpful curatorial tools in cases in which practitioners are working extensively with researchers from one scholarly domain, or one research team.

In this example, we worked extensively with Bruce Fouke, a geobiologist and co-PI of our project, to first inventory all data products (e.g. digital data such as spreadsheets, databases, gene sequences, field notes, field photographs, and more) from one field project, and then document a) how those data products were created, and b) how those data products were interlinked. The SBDC team's later work curating those data products was also identified.

The resulting workflow has 6 stages: Planning, Fieldwork, Processing & Analysis, Data Assessment, Standardizing and Packaging. 

### How to Read This Diagram 

The panels below represent different stages of research and curatorial work; each colored box corresponds to similarly colored documents and data products below. 

Each box with a red border represents a curatorial point of intervention identified through our work.


[image of workflow]

#### Key documents and data products

Each data product or sample is linked to its parent data products by arrows. 

Each element with < pointed corners > represents a standard, protocol or best practice.  

##### SBDC Minimum Information Guidelines
In consultation with geobiologists and YNP staff, we developed SBDC Minimum Information Guidelines, a set of core data and metadata elements necessary for documenting the context of geobiology data collection in the field. These include (but are not limited to) each sample’s location in relation to a hot spring’s vent; the temperature and pH of the water collected with each sample; field photographs; and more. For more information, please visit our SBDC Data Curation Guide: sitebaseddatacuration.wordpress.com   


[image of key documents and data products]





Though this initial workflow is specific to the field of geobiology -- and indeed, Dr. Fouke's particular field practices -- we are working with other researchers in other fields to document their research and curation workflows as well, and we hope that the resulting workflows can be altered and used by others.  


## References and further resources

The SBDC Guide [link](https://sitebaseddatacuration.wordpress.com/)

More on YNP [link](http://www.nps.gov/yell/index.htm)

## Acknowledgements
The SBDC project is a collaboration among information scientists, data archiving experts, geobiologists, and site resource managers at the University of Illinois at Urbana-Champaign, the University of Washington, Johns Hopkins University, and Yellowstone National Park. This presentation summarizes work conducted by the SBDC Team since 2012. Team members include: Carole Palmer (PI), Bruce Fouke, G. Sayeed Choudhury, Ann Rodman, Karen Baker, Jacob Jett, Abigail Asangba, Karen Wickett, Sean Gordon, and Christie Hendrix.

The SBDC Project has been funded through Institute of Museum and Library Service National Leadership Grant number LG-06-12-0706-12.