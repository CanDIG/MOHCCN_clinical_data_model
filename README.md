# MOHCCN Clinical Data Model

The [Marathon of Hope Cancer Centres Network](https://www.marathonofhopecancercentres.ca/) (MOHCCN) is a project to curate and share clinical and genomic data on Canadian cancer patients. The project has developed a clinical data model that is largely based on the [ICGC-ARGO Data Dictionary](https://docs.icgc-argo.org/dictionary). 

The most recent version of the data model, as well as supplementary material can always be found in the `Clinical Data Model` section of the MOHCCN [Policies and Guidelines](https://www.marathonofhopecancercentres.ca/researcher-hub/policies-and-guidelines) page. Here are direct download links to the various v3.0 documents:

* [Clinical Data Model v3.0](https://www.marathonofhopecancercentres.ca/docs/default-source/policies-and-guidelines/clinical-data-model-v3/mohccn_clinical_data_modelv3-0_may2024.xlsx?sfvrsn=80e1f917_1) (spreadsheet)
* Clinical Data Model v3.0 guidelines - not posted yet; coming soon. 
* [Clinical Data Model v3.0 release notes](https://www.marathonofhopecancercentres.ca/docs/default-source/policies-and-guidelines/clinical-data-model-v3/mohccn-clinical-data-model-release-notes_v3-0_may2024.pdf?sfvrsn=95d38d6e_1) (pdf)
* [Clinical Data Model v3.0 ER diagram](https://www.marathonofhopecancercentres.ca/docs/default-source/policies-and-guidelines/clinical-data-model-v3/mohccn_clinical_data_modelv3-0_er_diagram_may2024.png?sfvrsn=cdbcd90b_1) (pdf)

## Question about the model?

If you have questions about collecting data against the model, or implementing databases or tooling using the model, please create an issue in the [issue tracker](https://github.com/CanDIG/MOHCCN_clinical_data_model/issues). If you have a requests for changes or a general model inquiry, please fill out the form on the [MOHCCN Policies and Guidelines](https://www.marathonofhopecancercentres.ca/researcher-hub/policies-and-guidelines) page. 

## CanDIG implementations

CanDIG's implementation of the data model can be found in the [katsu](https://github.com/CanDIG/katsu) repository (our clinical data service using Django and PostgreSQL) and the [clinical_ETL_code](https://github.com/CanDIG/clinical_ETL_code) repository (a python library for mapping raw data to the model and generating json files for CanDIG ingest). Most of the data model validation happens in ETL, not katsu. 


