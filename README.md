# MOHCCN Clinical Data Model

The [Marathon of Hope Cancer Centres Network](https://www.marathonofhopecancercentres.ca/) (MOHCCN) is a project to curate and share clinical and genomic data on Canadian cancer patients. The project has developed a clinical data model that can be found on the [Policies and Guidelines](https://www.marathonofhopecancercentres.ca/researcher-hub/policies-and-guidelines) page. The model is largely based on the [ICGC-ARGO Data Dictionary](https://docs.icgc-argo.org/dictionary). 

## Question about the model?

If you have questions about collecting data against the model, or implementing databases or tooling using the model, please create an issue in the [issue tracker](https://github.com/CanDIG/MOHCCN_clinical_data_model/issues). 

## CanDIG implementations

CanDIG's implementation of the data model can be found in the [katsu](https://github.com/CanDIG/katsu) repository (our clinical data service using Django and PostgreSQL) and the [clinical_ETL_code](https://github.com/CanDIG/clinical_ETL_code) repository (a python library for mapping raw data to the model and generating json files for CanDIG ingest). Most of the data model validation happens in ETL, not katsu. 


