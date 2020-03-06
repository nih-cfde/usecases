---
layout: default
title: Portal Browse and Filter
nav_order: 1
parent: Use Cases
has_children: false
---
# Browse and Filter

**Persona:** [Clinical Researcher](../personas/clinical-researcher).

**Objective:** [Multiple DCC Comparison](../objectives/multi-dcc-comparison)

### Summary

Pams wants to build a table of the summarized metadata and summary statistics
from each RNA-Seq dataset in the Common Fund that relates to Focal Cortical Dysplasia.

Pam logs on to the CFDE portal and searches for brain data, and then filters the results to those studies that used RNASeq. She then searches within these results
for "FCD" or "Dysplasia".
The search results identify two CFDE programs with clinical data related to FCD: Kids First and HubMAP. Using links in the search results, Pam accesses the Program
page for each dataset, and decides which to request access to. She also sends
her final table to her postdoc, Lacey, who will do the actual analysis.


### User Tasks

-   [Open Access to CFDE portal](#open-access-to-cfde-portal)
-   [Search/filter data by anatomical site](#searchfilter-data-sets-by-phenotypic-terms)
-   [Search/filter data by data type terms](#searchfilter-data-sets-by-data-type-terms)
-   [Search within dataset descriptions](#search-within-dataset-descriptions)
-   [Visualize a table of all datasets that match query, by CF Program](#visualize-a-table-of-all-datasets-that-match-query-by-cf-program)
-   [Explore Program links](#explore-program-links)
-   [Share table with collaborator](#share-table-with-collaborator)

### Requirements

#### Open access to CFDE portal

-   The portal will support GUI web access to end users

or ?

-   Use any email address to access the CFDE portal to generate a user interface with access to public Common Fund metadata

#### Search/filter data sets by phenotypic terms

-   The portal shall support the selection of an anatomical term of interest

or ?

-   Use a list of phenotype concepts and the CFDE portal to search metadata and generate a subset of dataset identifiers from any CF Programs that matches researcher interests

#### Search/filter data sets by data type terms

-   The C2M2 model shall support information relating datatypes to CF programs
-   The catalog shall store information relating datatypes to CF programs

or ?

-   Use a list of datatype concepts and the CFDE portal to search metadata and generate a list of dataset identifiers from any multiple CF Programs.

#### Search within dataset descriptions

-   Use a disease term and search capability to search within metadata and generate a subset of dataset identifiers for multiple CF Programs.

#### Visualize a table of all datasets that match query, by CF Program

-   The catalog shall store information relating datasets to CF programs
-   The C2M2 model shall support information relating datasets to CF programs
-   The portal will render tables to display filtered data

or ?

-   Use an interactive graphical display (e.g. table and plots) to report on matching queries and their metadata.

#### Explore Program links

-   Use links in an interactive graphical display (e.g. table and plots) to
connect the user to data outside of the portal.

#### Share table with collaborator

-   Tables rendered in the portal are downloadable as csv
