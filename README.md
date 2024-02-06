# MOHCCN Clinical Data Model

The [Marathon of Hope Cancer Centres Network](https://www.marathonofhopecancercentres.ca/) (MOHCCN) is a project to curate and share clinical and genomic data on Canadian cancer patients. The project has developed a clinical data model that can be found on the . The model is largely based on the [ICGC-ARGO Data Dictionary](https://docs.icgc-argo.org/dictionary). 

The most recent version of the data model, as well as supplementary material can always be found in the `Clinical Data Model` section of the MOHCCN [Policies and Guidelines](https://www.marathonofhopecancercentres.ca/researcher-hub/policies-and-guidelines) page. Here are direct download links:

* [Clinical Data Model v2.1](https://www.marathonofhopecancercentres.ca/docs/default-source/policies-and-guidelines/clinical-data-model-v2.1/mohccn-clinical-data-model-v2.1_sep2023.xlsx?Status=Master&sfvrsn=611ca335_3) (spreadsheet)
* [Clinical Data Model guidelines](https://www.marathonofhopecancercentres.ca/docs/default-source/policies-and-guidelines/clinical-data-model-v2.1/mohccn-clinical-data-model-v2-guideline_6jun22.pdf?Status=Master&sfvrsn=cdd99e50_3) (pdf)
* [Clinical Data Model v 2.1 release notes](https://www.marathonofhopecancercentres.ca/docs/default-source/policies-and-guidelines/clinical-data-model-v2.1/mohccn-clinical-data-model-release-notes_sep2023.pdf?Status=Master&sfvrsn=19ece028_3) (pdf)

## Question about the model?

If you have questions about collecting data against the model, or implementing databases or tooling using the model, please create an issue in the [issue tracker](https://github.com/CanDIG/MOHCCN_clinical_data_model/issues). 

## CanDIG implementations

CanDIG's implementation of the data model can be found in the [katsu](https://github.com/CanDIG/katsu) repository (our clinical data service using Django and PostgreSQL) and the [clinical_ETL_code](https://github.com/CanDIG/clinical_ETL_code) repository (a python library for mapping raw data to the model and generating json files for CanDIG ingest). Most of the data model validation happens in ETL, not katsu. 


