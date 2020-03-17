---
layout: default
title: Portal Browse and Filter
nav_order: 1
parent: Use Cases
has_children: false
---
# Use Case 001 Browse and Filter

**Persona:** [Clinical Researcher](../personas/clinical-researcher).

**Objective:** [Multiple DCC Comparison](../objectives/multi-dcc-comparison)

### Summary

Pam wants to build a table of the summarized metadata and summary statistics
from each RNA-Seq dataset in the Common Fund that relates to Focal Cortical Dysplasia.

Pam logs on to the CFDE portal and searches for brain data, and then filters the results to those studies that used RNASeq. She then searches within these results
for "FCD" or "Dysplasia".
The search results identify two CFDE programs with clinical data related to FCD: Kids First and HubMAP. Using links in the search results, Pam accesses the Program
page for each dataset, and decides which to request access to. She also sends
her final table to her postdoc, Lacey, who will do the actual analysis.


### User Tasks

-   [Access CFDE portal](#access-cfde-portal)
-   [Search/filter data sets by phenotypic terms](#searchfilter-data-sets-by-phenotypic-terms)
-   [Search/filter data by data type terms](#searchfilter-data-sets-by-data-type-terms)
-   [Search within dataset descriptions](#search-within-dataset-descriptions)
-   [Visualize a table of all datasets that match query](#visualize-a-table-of-all-datasets-that-match-query)
-   [Explore Program links](#explore-program-links)
-   [Export a file of results](#export-a-file-of-results)

### Requirements

#### Access CFDE portal

-   The portal will support GUI web access to end users


#### Search/filter data sets by phenotypic terms

-   The portal shall support the selection of an anatomical term of interest


#### Search/filter data sets by data type terms

-   The C2M2 model shall support information relating datatypes to CF programs
-   The catalog shall store information relating datatypes to CF programs


#### Search within dataset descriptions

-   The portal will support free text search of results

#### Visualize a table of all datasets that match query

-   The catalog shall store information relating datasets to CF programs
-   The C2M2 model shall support information relating datasets to CF programs
-   The portal will render tables to display filtered data

#### Explore Program links

-   The portal will support links to original data sources within the results

#### Export a file of results

-   The portal shall support end user download of tables and figures in common formats
