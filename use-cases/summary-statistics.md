---
layout: default
title: Summary Statistics
nav_order: 3
parent: Summaries
has_children: true
---
# Monitor Data Releases as a Data Custodian

**Persona:** [Data Custodian](../personas/data-custodian).

**Objective:** [Monitor Data Releases](../objectives/single-dcc-release)

# Summary
Janice is the PI for data coordinating center. She would like
to use the CFDE dashboard to help write a progress report for her funding agency.
Using the browse and filter functions on the CFDE portal she creates a report
containing relevant summary statistics for datasets owned by her DCC, and
rendered graphs and figures of the summary data. This includes information such
as how much data is currently publicly available on her portal, how much is
uploaded but embargoed, the FAIRness score for these datasets, and how these
statistics have changed over the previous year.

### User Tasks

-   [Authorized Access to CFDE portal](#access-cfde-portal)
-   [Summarize all datatypes hosted by CF Program X](#summarize-all-datatypes-hosted-by-cf-program-x)
-   [Visualize a table of all datasets that match query](#visualize-a-table-of-all-datasets-that-match-query)
-   [Export a csv of results](#export-a-csv-of-results)

### Requirements

#### Access CFDE portal

-   The portal will support GUI web access to end users

or ?

-   Use eRA Commons ID to access the CFDE portal to generate a user interface with access to Common Fund oversight data

#### Search/filter Common Fund Programs by phenotypic terms

-   The portal shall support the selection of an anatomical term of interest.

or ?

-   Use a list of phenotype concepts and the CFDE portal to search metadata and generate a subset of CF Programs that matches researcher interests

#### Search/filter Common Fund Programs by data type terms

-   The C2M2 model shall support information relating datatypes to CF programs
-   The catalog shall store information relating datatypes to CF programs

or ?

-   Use a list of datatype concepts and the CFDE portal to search metadata and generate a list of CF Programs that matches researcher interests

#### Visualize a table of all datasets that match query

-   The catalog shall store information relating datasets to CF programs
-   The C2M2 model shall support information relating datasets to CF programs
-   The portal will render tables to display filtered data

or ?

-   Use an interactive graphical display (e.g. table and plots) to report on matching queries and their metadata.

#### Export a csv of results

-   Tables rendered in the portal are downloadable as csv
