# Data describing Biobank entity

## Definition
For MIABIS Core 3.0 purposes, Biobank is defined as **a legal entity or part of a legal entity that performs biobanking**, making the description aligned with ISO 20387:2018. In MIABIS biobank is an entity that stores samples and data related to the samples. In MIABIS Core 3.0 biobanks do not contain samples and data directly, as they are hosting sample collections to which the samples and data are embedded in. On the level of biobanks, only attributes related to the organizational aspect of the biobanks are represented (Eklund et al. Biopreserv Biobank. 2024; ,[in press]). 

## Attribute list

| Attribute Code | Attribute Name | Allowed Data | Description | Constraints| 
|---|---|---|---|---|
| MIABIS-BIOBANK-01 | ID | Text | ID of the biobank.|The ID is technical and given by the implementation. Implementation will provide instructions on how to form the ID.
| MIABIS-BIOBANK-02 | Acronym | Text | Short name in use for the biobank. If applicable.|
| MIABIS-BIOBANK-03 | Name | Text | Name of the biobank (preferably in English).|
| MIABIS-BIOBANK-04 | URL | Text | Complete http-address for the biobank.|
| MIABIS-BIOBANK-05 | Juristic Person | Text | Juristic person i.e. a university, concern, county council etc. for the biobank.|
| MIABIS-BIOBANK-06 | Country | Text | Two letter code for the country of the biobank.|ISO-standard 3166 alpha2.
| MIABIS-BIOBANK-07 | Contact Information | Structured data | Contact information for the contact person/person responsible of the biobank (Structured attribute) [MIABIS-BIOBANK-07](https://github.com/BBMRI-ERIC/miabis/blob/master/Structured-data-and-lists.md#contact-information).|
| MIABIS-BIOBANK-08 | Description | Text | Description of the biobank in English.|Free text description of the biobank. Recommendation max. 2000 char.
| MIABIS-BIOBANK-09 | Infrastructural capabilities | Enumerated values | The technical infrastructural capabilities that the biobank can offer to the clients. Can be one or more of the following values: Sample storage, Data storage, Biosafety abilities.|
| MIABIS-BIOBANK-10 | Organisational capabilities | Enumerated values | The organisational capabilities and services that the biobank can provide to support clients. Can be one or more of the following values: Recontact with donors, Facilitating clinical trials, Setting up prospective collections, Access to omics data, Access to laboratory analysis data, Access to donors'clinical data, Access to pathology archive, Access to radiology archive, Access to national medical registries, Other.
| MIABIS-BIOBANK-11 | Bioprocessing and analytical capabilities | Enumerated values | Bioprocessing and analytical services that the biobank can offer to the clients. Can be one or more of the following values: Biochemical analyses, Genomics, Nucleic acid extraction, Proteomics, Metabolomics, Histology, Cell-lines processing, Virology, Sample processing, Sample shipping, Sample quality control services, Other.
| MIABIS-BIOBANK-12 | Quality Management standard | Enumerated values | The standards that the biobank is certified or accredited for, Can be one or more of the following values: ISO 20387, ISO 9001, Other.|Attribute value list can be expanded by the implementation, and implementation needs to verify provided data.
