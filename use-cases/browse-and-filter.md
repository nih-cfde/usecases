---
layout: default
title: Browse and Filter
nav_order: 1
parent: Use Cases
has_children: false
---
# Browse and Filter

**Persona:** [Clinical Researcher](../personas/clinical-researcher).

**Objective:** [Multiple DCC Comparison](../objectives/multi-dcc-comparison)

### Summary

Pams wants to build a table of the summarized metadata and summary statistics (e.g., relevant studies, data types, number of participants, diagnoses) from each dataset
in the Common Fund that relate to Focal Cortical Dysplasia.

Pam searches by anatomical site, and then filters the results to those studies that used
RNASeq. The search results had identified two CFDE programs with clinical data
related to FCD: Kids First and HubMAP. HubMAP additionally includes genomics data,
which can be used to better understand the mechanism by which Pam's gene of
interest influences FCD, and Kids First includes genetic information that might
be useful for replicating Pam’s earlier findings in a new cohort.

Pam uses the results to start a dbGaP access request for her lab. She also sends
her final table to her postdoc, Lacey, who will do the actual analysis.

### User Tasks

-   [Access CFDE portal](#access-cfde-portal)
-   [Search/filter data by anatomical site](#searchfilter-data-by-anatomical-site)
-   [Search/filter data by data type](#search-filter-data-by-data-type)
-   [Visualize a table of all datasets that match query, by CF Program](#visualize-a-table-of-all-datasets)
-   [Share table with collaborator](#share-table-with-collaborator)

### Requirements

#### Access CFDE portal

-   The portal will support GUI web access to end users
or ?
-   Use eRA Commons ID to access the CFDE portal to generate a user interface with access to public Common Fund metadata

#### Search/filter data by anatomical site

-   The portal shall support the selection of an anatomical term of interest.
or ?
-   Use a list of phenotype concepts and the CFDE portal to search metadata and generate a subset of dataset identifiers for multiple CF Programs that matches researcher interests

#### Search/filter data by data type

-   The C2M2 model shall support information relating datatypes to CF programs
-   The catalog shall store information relating datatypes to CF programs
or ?
-   Use a list of datatype concepts and the CFDE portal to search metadata and generate a list of dataset identifiers for multiple CF Programs.

#### Visualize a table of all datasets that match query, by CF Program

-   The catalog shall store information relating datasets to CF programs
-   The C2M2 model shall support information relating datasets to CF programs
-   The portal will render tables to display filtered data

or ?

-   Use an interactive graphical display (e.g. table and plots) to report on matching queries and their metadata.

#### Share table with collaborator

-   Tables rendered in the portal are downloadable as csv
