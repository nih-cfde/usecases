---
layout: default
title: NIH Compare across DCCs
nav_order: 2
parent: Summaries
has_children: false
---

**Persona:** [Program Officer](../personas/program-officer).

**Objective:** [Multiple DCC Comparison](../objectives/multi-dcc-comparison)

### Explore data availability to build policy
Betsy is a leader at the Common Fund, and wants to build summary tables of
Common Fund assets for use in both tracking progress and for finding gaps that
should be filled by future initiatives. She would like to use the CFDE dashboard
to download simple tables or graphs that show what assets exist, and where.

Using a web browser, Betsy uses a point and click interface to get a matrix of
Uberon tissue terms by DCC. With a few more clicks, she gets similar tables showing
Species, and Experiment Types by Program.

Since these are simple binary matrices, Betsy can plot the data in almost any
piece of plotting software. Since she would like to see what terms are most broadly
and most infrequently found in the Common Fund, she opts for using UpSet, which
will automatically render her data in a type of multidimensional venn diagram.

### User Tasks

-   [Authorized Access to CFDE portal](#access-cfde-portal)
-   [Search/filter CF Programs by phenotypic terms](#searchfilter-common-fund-programs-by-phenotypic-terms)
-   [Search/filter CF Programs by data type terms](#search-filter-common-fund-programs-by-data-type terms)
-   [Visualize a table of all datasets that match query, by CF Program](#visualize-a-table-of-all-datasets)
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

#### Visualize a table of all datasets that match query, by CF Program

-   The catalog shall store information relating datasets to CF programs
-   The C2M2 model shall support information relating datasets to CF programs
-   The portal will render tables to display filtered data

or ?

-   Use an interactive graphical display (e.g. table and plots) to report on matching queries and their metadata.

#### Export a csv of results

-   Tables rendered in the portal are downloadable as csv
