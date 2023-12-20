## IOF Maintenance Ontology Class

In this class we provide an overview of the IOF-aligned Maintenance Reference ontology and demonstrate it's use of two application use cases (maintenance activities and failure mode).

### Part 1: Overview of the Maintenance Reference Ontology

Add link to file (MH to make)

Framing of the use cases

We will use the maintenance activity ontology and show how it can be used for monitoring the reliability of a pump. This could be e.g a lubrication or cooling water pump on some piece of manufacturing equipment used in producing the engine or for a jet engine oil system.

### Part 2: Maintenance activity ontoly

The use case is an instanciation of material described in a Semantic Web Journal paper `An ontology for maintenance activities and its application to data quality'.

A link to the Google CoLab file is here. (BDM to make)

A copy of the paper is available

https://content.iospress.com/download/semantic-web/sw233299?id=semantic-web%2Fsw233299

The abstract for the paper is below:

Maintenance of assets is a multi-million dollar cost each year for asset intensive organisations in the defence, manufacturing, resource and infrastructure sectors. These costs are tracked though maintenance work order (MWO) records. MWO records contain structured data for dates, costs, and asset identification and unstructured text describing the work required, for example `replace leaking pump'. Our focus in this paper is on data quality for maintenance activity terms in MWO records (e.g. replace, repair, adjust and inspect).

We present two contributions in this paper. First, we propose a reference ontology for maintenance activity terms. We use natural language processing to identify seven core maintenance activity terms and their synonyms from 800,000 MWOs. We provide elucidations for these seven terms. Second, we demonstrate use of the reference ontology in an application-level ontology using an industrial use case. The end-to-end NLP-ontology pipeline identifies data quality issues with 55% of the MWO records for a centrifugal pump over 8 years. For the 33% of records where a verb was not provided in the unstructured text, the ontology can infer a relevant activity class.

The selection of the maintenance activity terms is informed by the ISO 14224 and ISO 15926-4 standards and conforms to ISO/IEC 21838-2 Basic Formal Ontology (BFO). The reference and application ontologies presented here provide an example for how industrial organisations can augment their maintenance work management processes with ontological workflows to improve data quality.

A link to the GitHub file is

https://github.com/uwasystemhealth/Paper_Archive_Maintenance_Activity

### Part 3: Failure mode ontology

- MH and CW - to come.
