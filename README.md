## IOF Maintenance Ontology Class

In this class we provide an overview of the IOF-aligned Maintenance Reference ontology and demonstrate it's use of two application use cases (maintenance activities).

### Part 1: Overview of the Maintenance Reference Ontology

We will use power point slides to talk through the Maintenance Reference Ontology.

In addition it will be helpful for participants to access and look at the resources available on line.

Specifically

1. The IOF website hosting the IOF CORE, IOF supply chain and IOF maintenance ontologies

IOF GitHub: https://spec.industrialontologies.org/iof/
IOF Viewer: https://spec.industrialontologies.org/iof/ontology/
Direct link to the maintenance reference ontology: https://spec.industrialontologies.org/iof/ontology/maintenance/MaintenanceReferenceOntology/

2. The Ontocommons website and its metadata on ontologies as well as useful visualisations and search features on IOF-aligned maintenance ontologies

Maintenance reference ontology: https://spec.industrialontologies.org/iof/ontology/maintenance/MaintenanceReferenceOntology/
Maintenance

Maintenance activity ontology: https://industryportal.enit.fr/ontologies/MNT-ACT?p=summary

Maintenance procedure documentation ontology: https://industryportal.enit.fr/ontologies/OMPD-CMTO?p=summary

Note the FAIR scores available for each, a licence, a hyperlink to the source, and a figure.

We will start with materials in the Powerpoint - powerpoint\IOF-maintenance-workshop-2024.pptx

### Part 2: Use case - Maintenance activity ontology

Framing of the use case

We will use the maintenance activity ontology and show how it can be used for monitoring the reliability of a pump. This could be e.g a lubrication or cooling water pump on some piece of manufacturing equipment used in producing the engine or for a jet engine oil system.

The use case is an instanciation of material described in a Semantic Web Journal paper `An ontology for maintenance activities and its application to data quality'.

A link to the Google CoLab file is here https://colab.research.google.com/drive/1gVgtC-JcXikNPzpp8p1wIGstF0EEnwBl?usp=sharing

A copy of the paper is available

https://content.iospress.com/download/semantic-web/sw233299?id=semantic-web%2Fsw233299

The abstract for the paper is below:

Maintenance of assets is a multi-million dollar cost each year for asset intensive organisations in the defence, manufacturing, resource and infrastructure sectors. These costs are tracked though maintenance work order (MWO) records. MWO records contain structured data for dates, costs, and asset identification and unstructured text describing the work required, for example `replace leaking pump'. Our focus in this paper is on data quality for maintenance activity terms in MWO records (e.g. replace, repair, adjust and inspect).

We present two contributions in this paper. First, we propose a reference ontology for maintenance activity terms. We use natural language processing to identify seven core maintenance activity terms and their synonyms from 800,000 MWOs. We provide elucidations for these seven terms. Second, we demonstrate use of the reference ontology in an application-level ontology using an industrial use case. The end-to-end NLP-ontology pipeline identifies data quality issues with 55% of the MWO records for a centrifugal pump over 8 years. For the 33% of records where a verb was not provided in the unstructured text, the ontology can infer a relevant activity class.

The selection of the maintenance activity terms is informed by the ISO 14224 and ISO 15926-4 standards and conforms to ISO/IEC 21838-2 Basic Formal Ontology (BFO). The reference and application ontologies presented here provide an example for how industrial organisations can augment their maintenance work management processes with ontological workflows to improve data quality.

A link to the GitHub file for the paper is

https://github.com/uwasystemhealth/Paper_Archive_Maintenance_Activity
